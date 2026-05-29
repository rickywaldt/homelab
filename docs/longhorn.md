# Longhorn

## Reinstall Longhorn

Remove Longhorn, then run:

```
flux reconcile kustomization infrastructure --with-source
```

You might get a timeout waiting for namespace Longhorn terminating message. In that case run the following command:

```
kubectl get crd | grep longhorn | awk {'print $1'} | xargs kubectl delete crd
```

This command will effectively delete all longhorn crd's.

```
for crd in $(kubectl get crds | grep longhorn | awk '{print $1}'); do
  kubectl get $crd -A -o name | while read obj; do
    kubectl patch $obj --type=merge -p '{"metadata":{"finalizers":[]}}'
  done
done
```

This for loop will effectively remove Kubernetes finalizers from all Longhorn crd's. Only run this if the previous command did not succeed to delete all Longhorn crd's.

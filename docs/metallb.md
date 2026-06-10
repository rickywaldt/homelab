# MetalLB

There are 3 resources deployed in the metallb-system namespace: metallb, IP address pool, and layer-2 advertisement.

1. MetalLB is the main instance of MetalLB that the MetalLB operator deploys.
2. The pool of IP's that MetalLB can hand out to the LoadBalancer services.
3. The layer-2 advertisement that links to the pool of IP's.

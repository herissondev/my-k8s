# Custom Traefik configuration

Replaced the default microk8s Ingress controller with Traefik.
Easier to configure and more powerful.

Automatically creates a certificate for my domains, easy midlewares, split traffic...

The default Ingrees controller needs to be disabled:

Deployed on the `traefik` namespace.
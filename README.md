# auto-pilot

## Description

This repo uses [ArgoCD's Auto Pilot](https://argocd-autopilot.readthedocs.io/en/stable/Getting-Started/) to boot strap a Kubernetes cluster.

## Deployent

To boot strap a Kubernetes cluster run this command:

```
argocd-autopilot repo bootstrap --recover
```

## Apps

The applications in this ArgoCD application set will be installed automatically.

+ [cluster-addons](https://github.com/polinchw/cluster-addons) (This will use the values-dev.yaml durning the installation.)
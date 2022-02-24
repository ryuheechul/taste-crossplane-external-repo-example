# external-repo

This is to show the example of an external repository being used for [Crossplane + FluxCD](https://github.com/ryuheechul/taste-crossplane).

## How Is This Path Is Being Used for Deployment?
In this repo's case it's at [ryuheechul/taste-crossplane/blob/main/clusters/local/external/flux-kustomization.yaml](https://github.com/ryuheechul/taste-crossplane/blob/main/clusters/local/external/flux-kustomization.yaml).

## Verify the Deployment
> make sure that you are running the Crossplane (Kubernetes) cluster via [github.com/ryuheechul/taste-crossplane](https://github.com/ryuheechul/taste-crossplane) first

`kubectl describe object.kubernetes.crossplane.io external-repo-via-fluxcd` or [`make status`](https://github.com/ryuheechul/taste-crossplane/blob/3ea2b53201af3e06363366374e43dfc22660fbe1/Makefile#L9)

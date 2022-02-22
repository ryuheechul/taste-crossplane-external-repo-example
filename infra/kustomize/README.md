Since we expect this repository to be pulled via FluxCD (especially via [Kustomization](https://fluxcd.io/docs/components/kustomize/kustomization/)) it's good to group them under this directory.

It's also probably good idea to link the "parent" repository that defines the relationship in here.

In this repo's case it's at [ryuheechul/taste-crossplane/blob/main/clusters/local/external-repo-source.yaml](https://github.com/ryuheechul/taste-crossplane/blob/main/clusters/local/external-repo-source.yaml).

Also see [external-repo](./external-repo)

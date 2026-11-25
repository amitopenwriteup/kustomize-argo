# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/amitopenwriteup/kustomize-argo.git
# cd into the cloned directory
git checkout 4c04e6f06570b8b482541b058d2e9aaed0dece08
kustomize build ./overlays/prod
```

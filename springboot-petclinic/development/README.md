# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/anandf/rendered-manifests-examples
# cd into the cloned directory
git checkout 341705f41a83b145a6bd502a55cbf066f2e855c6
kustomize build ./springboot-petclinic/development
```

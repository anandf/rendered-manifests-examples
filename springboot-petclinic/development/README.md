# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/anandf/rendered-manifests-examples
# cd into the cloned directory
git checkout 641e894d5c85fd2a89ebe5dd3bf730aeddabca65
kustomize build ./springboot-petclinic/development
```

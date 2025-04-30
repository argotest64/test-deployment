
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/test-deployment.git
# cd into the cloned directory
git checkout 041d13e73aa6793f132e8d50dd50c4be26880053
helm template . --name-template testapp1-prod-r1 --include-crds
```
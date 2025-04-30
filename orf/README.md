
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/test-deployment.git
# cd into the cloned directory
git checkout 40abd4ce40809cd68a98a211a7f05ea44187b56c
helm template . --name-template testapp1-prod-r1 --include-crds
```
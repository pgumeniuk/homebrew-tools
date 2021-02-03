# homebrew-tools
Tap with handy tools for daily duities.

## helm v2.14.3
Custom brew formulae which will not conflict with existing helm 3 installations.
```bash
brew install pgumeniuk/tools/helm@2.14
```

## kubectl v1.15.12 
You must use a kubectl version that is within one minor version difference of your cluster.
For example, a v1.14 client should work with v1.13, v1.14, and v1.15 master.
Using the latest version of kubectl helps avoid unforeseen issues.
```bash
brew install pgumeniuk/tools/kubernetes-cli@1.15
```

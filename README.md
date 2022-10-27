# Fleet Example to demonstrate the Cilium Clustermesh

```
apiVersion: fleet.cattle.io/v1alpha1
kind: GitRepo
metadata:
  name: fleet-mesh-example
  namespace: fleet-default
spec:
  branch: main
  repo: https://github.com/dgiebert/fleet-mesh-example.git
  targets:
  - clusterSelector: {}
```
# Tanzu Apps Cluster Supply Chain Get

`tanzu apps cluster-supply-chain get` command is used to get a detailed information of the cluster supply chain

## Default view

The default view of `get` command shows the status of the supply chain, and the selectors that a workload must match so it's taken by that workload

For example:

```console
$ tanzu apps cluster-supply-chain get source-to-url
---
# source-to-url: Ready
---
Supply Chain Selectors
TYPE     KEY                                   OPERATOR   VALUE
labels   apps.tanzu.vmware.com/workload-type              web
```

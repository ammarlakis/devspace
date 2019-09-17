---
title: Command - devspace list clusters
sidebar_label: clusters
id: version-v4.0.0-devspace_list_clusters
original_id: devspace_list_clusters
---


Lists all connected clusters

## Synopsis


```
devspace list clusters [flags]
```

```
#######################################################
############## devspace list clusters #################
#######################################################
List all connected user clusters

Example:
devspace list clusters
#######################################################
```
## Options

```
      --all               Show all available clusters including hosted DevSpace cloud clusters
  -h, --help              help for clusters
      --provider string   Cloud Provider to use
```

### Options inherited from parent commands

```
      --debug                 Prints the stack trace if an error occurs
      --kube-context string   The kubernetes context to use
  -n, --namespace string      The kubernetes namespace to use
      --no-warn               If true does not show any warning when deploying into a different namespace or kube-context than before
  -p, --profile string        The devspace profile to use (if there is any)
      --silent                Run in silent mode and prevents any devspace log output except panics & fatals
      --var strings           Variables to override during execution (e.g. --var=MYVAR=MYVALUE)
```

## See Also

* [devspace list](/docs/cli/commands/devspace_list)	 - Lists configuration

###### Auto generated by spf13/cobra on 13-Sep-2019
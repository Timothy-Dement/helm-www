---
title: "Helm Get"
---

## helm get

download extended information of a named release

### Synopsis


This command consists of multiple subcommands which can be used to
get extended information about the release, including:

- The values used to generate the release
- The generated manifest file
- The notes provided by the chart of the release
- The hooks associated with the release


### Options

```
  -h, --help   help for get
```

### Options inherited from parent commands

```
      --debug                       enable verbose output
      --kube-apiserver string       the address and the port for the Kubernetes API server
      --kube-as-group stringArray   group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --kube-as-user string         username to impersonate for the operation
      --kube-ca-file string         the certificate authority file for the Kubernetes API server connection
      --kube-context string         name of the kubeconfig context to use
      --kube-token string           bearer token used for authentication
      --kubeconfig string           path to the kubeconfig file
  -n, --namespace string            namespace scope for this request
      --registry-config string      path to the registry config file (default "~/.config/helm/registry/config.json")
      --repository-cache string     path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string    path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
```

### SEE ALSO

* [helm](helm.md)	 - The Helm package manager for Kubernetes.
* [helm get all](helm_get_all.md)	 - download all information for a named release
* [helm get hooks](helm_get_hooks.md)	 - download all hooks for a named release
* [helm get manifest](helm_get_manifest.md)	 - download the manifest for a named release
* [helm get notes](helm_get_notes.md)	 - download the notes for a named release
* [helm get values](helm_get_values.md)	 - download the values file for a named release

###### Auto generated by spf13/cobra on 24-Jan-2022

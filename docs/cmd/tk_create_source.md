## tk create source

Create or update sources

### Synopsis

The create source sub-commands generate sources.

### Options

```
  -h, --help   help for source
```

### Options inherited from parent commands

```
      --export              export in YAML format to stdout
      --interval duration   source sync interval (default 1m0s)
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
      --namespace string    the namespace scope for this operation (default "gitops-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [tk create](tk_create.md)	 - Create or update sources and resources
* [tk create source git](tk_create_source_git.md)	 - Create or update a GitRepository source
* [tk create source helm](tk_create_source_helm.md)	 - Create or update a HelmRepository source


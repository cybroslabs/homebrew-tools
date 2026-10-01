## kubectl omq storage

Manage OctopusMQ storages

### Synopsis

The 'storage' command provides subcommands for managing key-value storages and their data in OctopusMQ.

### Options

```
  -h, --help   help for storage
```

### Options inherited from parent commands

```
      --as string                      Username to impersonate for the operation. User could be a regular user or a service account in a namespace.
      --as-group stringArray           Group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --as-uid string                  UID to impersonate for the operation.
      --as-user-extra stringArray      User extras to impersonate for the operation, this flag can be repeated to specify multiple values for the same key.
      --cache-dir string               Default cache directory (default "/root/.kube/cache")
      --certificate-authority string   Path to a cert file for the certificate authority
      --client-certificate string      Path to a client certificate file for TLS
      --client-key string              Path to a client key file for TLS
      --cluster string                 The name of the kubeconfig cluster to use
      --context string                 The name of the kubeconfig context to use
      --disable-compression            If true, opt-out of response compression for all requests to the server
      --insecure-skip-tls-verify       If true, the server's certificate will not be checked for validity. This will make your HTTPS connections insecure
      --kubeconfig string              Path to the kubeconfig file to use for CLI requests.
  -n, --namespace string               If present, the namespace scope for this CLI request
      --no-color                       Disable colored output (also disabled by the NO_COLOR environment variable or when output is not a terminal)
  -o, --output string                  Output format: console, json (default "console")
      --proxy-url string               Proxy URL to use for requests to the API server
      --request-timeout string         The length of time to wait before giving up on a single server request. Non-zero values should contain a corresponding time unit (e.g. 1s, 2m, 3h). A value of zero means don't timeout requests. (default "0")
  -s, --server string                  The address and port of the Kubernetes API server
      --tls-server-name string         Server name to use for server certificate validation. If it is not provided, the hostname used to contact the server is used
      --token string                   Bearer token for authentication to the API server
      --user string                    The name of the kubeconfig user to use
  -v, --verbosity int8                 Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [kubectl omq](kubectl_omq.md)	 - Manage OctopusMQ clusters in Kubernetes
* [kubectl omq storage create](kubectl_omq_storage_create.md)	 - Create a new storage
* [kubectl omq storage delete](kubectl_omq_storage_delete.md)	 - Delete a storage
* [kubectl omq storage delete-key](kubectl_omq_storage_delete-key.md)	 - Delete a key from a storage
* [kubectl omq storage ensure](kubectl_omq_storage_ensure.md)	 - Create a storage if it does not exist
* [kubectl omq storage get](kubectl_omq_storage_get.md)	 - Get a value by key from a storage
* [kubectl omq storage get-keys](kubectl_omq_storage_get-keys.md)	 - List all keys in a storage
* [kubectl omq storage info](kubectl_omq_storage_info.md)	 - Show detailed storage information
* [kubectl omq storage list](kubectl_omq_storage_list.md)	 - List all storages
* [kubectl omq storage lock-any](kubectl_omq_storage_lock-any.md)	 - Lock any available item in a storage
* [kubectl omq storage noop](kubectl_omq_storage_noop.md)	 - Send a no-op to a storage
* [kubectl omq storage set](kubectl_omq_storage_set.md)	 - Set a key-value pair in a storage


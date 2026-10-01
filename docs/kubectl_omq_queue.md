## kubectl omq queue

Manage OctopusMQ queues

### Synopsis

The 'queue' command provides subcommands for managing queues and their data in OctopusMQ.

### Options

```
  -h, --help   help for queue
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
* [kubectl omq queue create](kubectl_omq_queue_create.md)	 - Create a new queue
* [kubectl omq queue delete](kubectl_omq_queue_delete.md)	 - Delete a queue
* [kubectl omq queue delete-item](kubectl_omq_queue_delete-item.md)	 - Delete items from a queue
* [kubectl omq queue enqueue](kubectl_omq_queue_enqueue.md)	 - Enqueue an item into a queue
* [kubectl omq queue ensure](kubectl_omq_queue_ensure.md)	 - Create a queue if it does not exist
* [kubectl omq queue info](kubectl_omq_queue_info.md)	 - Show detailed queue information
* [kubectl omq queue list](kubectl_omq_queue_list.md)	 - List all queues
* [kubectl omq queue noop](kubectl_omq_queue_noop.md)	 - Send a no-op to a queue
* [kubectl omq queue pause](kubectl_omq_queue_pause.md)	 - Pause a queue
* [kubectl omq queue pull](kubectl_omq_queue_pull.md)	 - Pull items from a queue
* [kubectl omq queue resize](kubectl_omq_queue_resize.md)	 - Resize a queue
* [kubectl omq queue resume](kubectl_omq_queue_resume.md)	 - Resume a queue


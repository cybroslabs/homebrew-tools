## kubectl omq test

Run tests against an OctopusMQ instance

### Synopsis

The 'test' command provides subcommands for running performance benchmarks
and correctness verification against an OctopusMQ instance.

### Options

```
      --batch-size int32        Batch size for pull operations (default 10)
      --concurrency int         Number of concurrent producer/consumer goroutines (default 4)
  -h, --help                    help for test
      --message-size int        Payload size in bytes (minimum 8) (default 256)
      --min-duration duration   Minimum duration per scenario before stopping (e.g. 10s, 1m) (default 10s)
      --priorities uint32       Number of priority levels for the queue (default 3)
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
* [kubectl omq test benchmark](kubectl_omq_test_benchmark.md)	 - Run performance benchmarks against an OctopusMQ instance
* [kubectl omq test verify](kubectl_omq_test_verify.md)	 - Run correctness verification tests


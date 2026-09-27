## omqctl

Command-line tool for OctopusMQ deployments

### Synopsis

omqctl is a command-line interface for managing OctopusMQ deployments. It manages queues, storages, and their data through the OctopusMQ gRPC API.

### Options

```
      --context string   Context to use for the command (uses the active context if not specified)
  -h, --help             help for omqctl
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl config](omqctl_config.md)	 - Manage omqctl configuration
* [omqctl queue](omqctl_queue.md)	 - Manage OctopusMQ queues
* [omqctl storage](omqctl_storage.md)	 - Manage OctopusMQ storages
* [omqctl test](omqctl_test.md)	 - Run tests against an OctopusMQ instance
* [omqctl version](omqctl_version.md)	 - Print the client version information


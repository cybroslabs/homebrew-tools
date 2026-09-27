## omqctl storage

Manage OctopusMQ storages

### Synopsis

The 'storage' command provides subcommands for managing key-value storages and their data in OctopusMQ.

### Options

```
  -h, --help   help for storage
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl](omqctl.md)	 - Command-line tool for OctopusMQ deployments
* [omqctl storage create](omqctl_storage_create.md)	 - Create a new storage
* [omqctl storage delete](omqctl_storage_delete.md)	 - Delete a storage
* [omqctl storage delete-key](omqctl_storage_delete-key.md)	 - Delete a key from a storage
* [omqctl storage ensure](omqctl_storage_ensure.md)	 - Create a storage if it does not exist
* [omqctl storage get](omqctl_storage_get.md)	 - Get a value by key from a storage
* [omqctl storage get-keys](omqctl_storage_get-keys.md)	 - List all keys in a storage
* [omqctl storage info](omqctl_storage_info.md)	 - Show detailed storage information
* [omqctl storage list](omqctl_storage_list.md)	 - List all storages
* [omqctl storage lock-any](omqctl_storage_lock-any.md)	 - Lock any available item in a storage
* [omqctl storage noop](omqctl_storage_noop.md)	 - Send a no-op to a storage
* [omqctl storage set](omqctl_storage_set.md)	 - Set a key-value pair in a storage


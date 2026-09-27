## omqctl storage delete-key

Delete a key from a storage

### Synopsis

The 'storage delete-key' command removes a key and its value from the specified storage.

```
omqctl storage delete-key <storage> [flags]
```

### Options

```
  -h, --help         help for delete-key
      --key string   Key to delete
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl storage](omqctl_storage.md)	 - Manage OctopusMQ storages


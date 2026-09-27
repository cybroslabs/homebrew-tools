## omqctl storage set

Set a key-value pair in a storage

### Synopsis

The 'storage set' command sets a key-value pair in the specified storage, replacing any existing value.

```
omqctl storage set <storage> [flags]
```

### Options

```
  -h, --help                help for set
      --key string          Key to set
      --ttl duration        Time-to-live (e.g. 30s, 5m, 1h)
      --value string        Value to set
      --value-file string   File containing the value to set
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl storage](omqctl_storage.md)	 - Manage OctopusMQ storages


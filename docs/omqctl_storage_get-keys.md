## omqctl storage get-keys

List all keys in a storage

### Synopsis

The 'storage get-keys' command lists all keys in the specified storage, including locked ones.
Keys that are not printable ASCII are shown as "base64:<data>".

```
omqctl storage get-keys <storage> [flags]
```

### Options

```
  -h, --help   help for get-keys
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl storage](omqctl_storage.md)	 - Manage OctopusMQ storages


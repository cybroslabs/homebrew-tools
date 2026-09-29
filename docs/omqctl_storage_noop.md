## omqctl storage noop

Send a no-op to a storage

### Synopsis

The 'storage noop' command sends a no-op request to the specified storage to check that it is reachable.

```
omqctl storage noop <storage> [flags]
```

### Options

```
  -h, --help   help for noop
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
      --no-color         Disable colored output (also disabled by the NO_COLOR environment variable or when output is not a terminal)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl storage](omqctl_storage.md)	 - Manage OctopusMQ storages


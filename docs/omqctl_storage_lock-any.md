## omqctl storage lock-any

Lock any available item in a storage

### Synopsis

The 'storage lock-any' command locks any available item in the specified storage and prints it.

The lock is held only while the command runs: the item is released when the command exits.
With --delete, the item is deleted instead, which takes it out of the storage.

When no item becomes available within --timeout, the command prints an empty result.

```
omqctl storage lock-any <storage> [flags]
```

### Options

```
      --delete             Delete the locked item before exiting
  -h, --help               help for lock-any
      --timeout duration   How long to wait for an available item (default 15s)
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


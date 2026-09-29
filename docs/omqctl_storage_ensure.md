## omqctl storage ensure

Create a storage if it does not exist

### Synopsis

The 'storage ensure' command creates a storage only if it does not already exist, so the command is idempotent.

```
omqctl storage ensure <name> [flags]
```

### Options

```
  -h, --help   help for ensure
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


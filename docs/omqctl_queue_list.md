## omqctl queue list

List all queues

### Synopsis

The 'queue list' command lists all queues in the OctopusMQ instance.

```
omqctl queue list [flags]
```

### Options

```
  -h, --help   help for list
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
      --no-color         Disable colored output (also disabled by the NO_COLOR environment variable or when output is not a terminal)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl queue](omqctl_queue.md)	 - Manage OctopusMQ queues


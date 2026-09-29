## omqctl queue ensure

Create a queue if it does not exist

### Synopsis

The 'queue ensure' command creates a queue only if it does not already exist. An existing queue is left unchanged, so the command is idempotent.

```
omqctl queue ensure <name> [flags]
```

### Options

```
  -h, --help                help for ensure
      --max-size uint32     Maximum queue size (0 = unlimited)
      --priorities uint32   Number of priority levels (default 1)
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


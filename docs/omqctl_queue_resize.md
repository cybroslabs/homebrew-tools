## omqctl queue resize

Resize a queue

### Synopsis

The 'queue resize' command changes the maximum size of the specified queue.

```
omqctl queue resize <name> [flags]
```

### Options

```
  -h, --help              help for resize
      --max-size uint32   New maximum queue size (0 = unlimited)
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl queue](omqctl_queue.md)	 - Manage OctopusMQ queues


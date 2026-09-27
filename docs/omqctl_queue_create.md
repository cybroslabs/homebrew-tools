## omqctl queue create

Create a new queue

### Synopsis

The 'queue create' command creates a new queue with the specified name and options. It fails if the queue already exists.

```
omqctl queue create <name> [flags]
```

### Options

```
  -h, --help                help for create
      --max-size uint32     Maximum queue size (0 = unlimited)
      --priorities uint32   Number of priority levels (default 1)
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl queue](omqctl_queue.md)	 - Manage OctopusMQ queues


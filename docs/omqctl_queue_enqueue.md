## omqctl queue enqueue

Enqueue an item into a queue

### Synopsis

The 'queue enqueue' command adds an item to the specified queue.

```
omqctl queue enqueue <queue> [flags]
```

### Options

```
      --grouping-key string   Grouping key
  -h, --help                  help for enqueue
      --priority uint32       Priority level
      --ttl duration          Time-to-live (e.g. 30s, 5m, 1h)
      --unique-key string     Unique key for deduplication
      --value string          Value to enqueue
      --value-file string     File containing the value to enqueue
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl queue](omqctl_queue.md)	 - Manage OctopusMQ queues


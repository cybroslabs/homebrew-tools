## omqctl queue delete-item

Delete items from a queue

### Synopsis

The 'queue delete-item' command permanently removes items from the queue by their IDs.

```
omqctl queue delete-item <queue> [flags]
```

### Options

```
  -h, --help         help for delete-item
      --ids string   Comma-separated list of item IDs to delete
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl queue](omqctl_queue.md)	 - Manage OctopusMQ queues


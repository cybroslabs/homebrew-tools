## omqctl queue pull

Pull items from a queue

### Synopsis

The 'queue pull' command retrieves items from the specified queue.

Without --commit, the pulled items are returned to the queue when the command exits,
so the command only inspects the items at the head of the queue. With --commit, the
items are committed before the command exits and are removed from the queue.

When no item becomes available within --timeout, the command prints an empty result.

```
omqctl queue pull <queue> [flags]
```

### Options

```
      --batch-size int32   Maximum number of items to pull (default 1)
      --commit             Commit the pulled items, removing them from the queue
  -h, --help               help for pull
      --timeout duration   How long to wait for items (default 15s)
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


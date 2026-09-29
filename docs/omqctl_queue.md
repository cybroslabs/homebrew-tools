## omqctl queue

Manage OctopusMQ queues

### Synopsis

The 'queue' command provides subcommands for managing queues and their data in OctopusMQ.

### Options

```
  -h, --help   help for queue
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
      --no-color         Disable colored output (also disabled by the NO_COLOR environment variable or when output is not a terminal)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl](omqctl.md)	 - Command-line tool for OctopusMQ deployments
* [omqctl queue create](omqctl_queue_create.md)	 - Create a new queue
* [omqctl queue delete](omqctl_queue_delete.md)	 - Delete a queue
* [omqctl queue delete-item](omqctl_queue_delete-item.md)	 - Delete items from a queue
* [omqctl queue enqueue](omqctl_queue_enqueue.md)	 - Enqueue an item into a queue
* [omqctl queue ensure](omqctl_queue_ensure.md)	 - Create a queue if it does not exist
* [omqctl queue info](omqctl_queue_info.md)	 - Show detailed queue information
* [omqctl queue list](omqctl_queue_list.md)	 - List all queues
* [omqctl queue noop](omqctl_queue_noop.md)	 - Send a no-op to a queue
* [omqctl queue pause](omqctl_queue_pause.md)	 - Pause a queue
* [omqctl queue pull](omqctl_queue_pull.md)	 - Pull items from a queue
* [omqctl queue resize](omqctl_queue_resize.md)	 - Resize a queue
* [omqctl queue resume](omqctl_queue_resume.md)	 - Resume a queue


## omqctl replica

Manage OctopusMQ replicas

### Synopsis

The 'replica' command provides subcommands for inspecting the replicas of an OctopusMQ cluster and for destroying one so that it resynchronizes from the leader.

### Options

```
  -h, --help   help for replica
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
* [omqctl replica destroy](omqctl_replica_destroy.md)	 - Destroy a replica so that it resyncs from the leader
* [omqctl replica list](omqctl_replica_list.md)	 - List the replicas of the cluster


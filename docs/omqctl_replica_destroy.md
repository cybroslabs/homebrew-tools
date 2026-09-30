## omqctl replica destroy

Destroy a replica so that it resyncs from the leader

### Synopsis

The 'replica destroy' command removes the replica with the given ordinal from the cluster. The replica deletes its data and rejoins the cluster at its next start, when it resynchronizes from the leader.

The cluster refuses to destroy a replica when that would break the quorum or while another replica is resynchronizing. The command retries while the leadership moves, until --timeout elapses. With --wait, it then waits until the replica is a voter again, replicating with a lag of at most 1000 entries.

Without --yes, the command asks for confirmation on a terminal and refuses to run otherwise.

```
omqctl replica destroy <ordinal> [flags]
```

### Options

```
  -h, --help               help for destroy
      --timeout duration   Time allowed for the command, including --wait (default 10m0s)
      --wait               Wait until the replica is back in the cluster and caught up
  -y, --yes                Do not ask for confirmation
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
      --no-color         Disable colored output (also disabled by the NO_COLOR environment variable or when output is not a terminal)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl replica](omqctl_replica.md)	 - Manage OctopusMQ replicas


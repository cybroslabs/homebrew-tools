## omqctl test verify

Run correctness verification tests

### Synopsis

The 'test verify' command creates a temporary queue and runs a series of
correctness verification tests (grouping isolation, priority ordering),
printing step-by-step pass/fail results. The test queue is always deleted on completion.

```
omqctl test verify [flags]
```

### Options

```
  -h, --help                help for verify
      --scenarios strings   Run only specified scenarios (comma-separated: grouping-isolation, priority-ordering)
```

### Options inherited from parent commands

```
      --batch-size int32        Batch size for pull operations (default 10)
      --concurrency int         Number of concurrent producer/consumer goroutines (default 4)
      --context string          Context to use for the command (uses the active context if not specified)
      --message-size int        Payload size in bytes (minimum 8) (default 256)
      --min-duration duration   Minimum duration per scenario before stopping (e.g. 10s, 1m) (default 10s)
      --no-color                Disable colored output (also disabled by the NO_COLOR environment variable or when output is not a terminal)
  -o, --output string           Output format: console, json (default "console")
      --priorities uint32       Number of priority levels for the queue (default 3)
  -v, --verbosity int8          Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl test](omqctl_test.md)	 - Run tests against an OctopusMQ instance


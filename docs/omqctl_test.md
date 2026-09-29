## omqctl test

Run tests against an OctopusMQ instance

### Synopsis

The 'test' command provides subcommands for running performance benchmarks
and correctness verification against an OctopusMQ instance.

### Options

```
      --batch-size int32        Batch size for pull operations (default 10)
      --concurrency int         Number of concurrent producer/consumer goroutines (default 4)
  -h, --help                    help for test
      --message-size int        Payload size in bytes (minimum 8) (default 256)
      --min-duration duration   Minimum duration per scenario before stopping (e.g. 10s, 1m) (default 10s)
      --priorities uint32       Number of priority levels for the queue (default 3)
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
* [omqctl test benchmark](omqctl_test_benchmark.md)	 - Run performance benchmarks against an OctopusMQ instance
* [omqctl test verify](omqctl_test_verify.md)	 - Run correctness verification tests


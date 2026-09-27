## omqctl test benchmark

Run performance benchmarks against an OctopusMQ instance

### Synopsis

The 'test benchmark' command creates a temporary queue, runs a series of performance
benchmarks (throughput, keyed messages, grouping, deduplication),
and prints a report. The test queue is always deleted on completion or interruption.

Each scenario runs for at least --min-duration before stopping, so that the
measurements are stable.

```
omqctl test benchmark [flags]
```

### Options

```
  -h, --help                help for benchmark
      --scenarios strings   Run only specified scenarios (comma-separated: enqueue, pull, mixed, grouping, dedup, empty)
```

### Options inherited from parent commands

```
      --batch-size int32        Batch size for pull operations (default 10)
      --concurrency int         Number of concurrent producer/consumer goroutines (default 4)
      --context string          Context to use for the command (uses the active context if not specified)
      --message-size int        Payload size in bytes (minimum 8) (default 256)
      --min-duration duration   Minimum duration per scenario before stopping (e.g. 10s, 1m) (default 10s)
  -o, --output string           Output format: console, json (default "console")
      --priorities uint32       Number of priority levels for the queue (default 3)
  -v, --verbosity int8          Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl test](omqctl_test.md)	 - Run tests against an OctopusMQ instance


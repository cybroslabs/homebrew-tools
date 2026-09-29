## omqctl config get-context

Display the current active context

### Synopsis

The 'config get-context' command prints the name of the currently active context.

```
omqctl config get-context [flags]
```

### Options

```
  -h, --help   help for get-context
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
      --no-color         Disable colored output (also disabled by the NO_COLOR environment variable or when output is not a terminal)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl config](omqctl_config.md)	 - Manage omqctl configuration


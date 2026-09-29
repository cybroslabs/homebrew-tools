## omqctl config set-context

Set the active context

### Synopsis

The 'config set-context' command switches the active context to the specified name and saves it to the configuration file.

```
omqctl config set-context <name> [flags]
```

### Options

```
  -h, --help   help for set-context
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


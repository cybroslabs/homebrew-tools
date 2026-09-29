## omqctl config

Manage omqctl configuration

### Synopsis

The 'config' command provides subcommands for viewing and managing the omqctl configuration file.

The file is read from ~/.omq/config, or from the path in the OMQCONFIG environment variable.

### Options

```
  -h, --help   help for config
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
* [omqctl config get-context](omqctl_config_get-context.md)	 - Display the current active context
* [omqctl config list-contexts](omqctl_config_list-contexts.md)	 - List all available contexts
* [omqctl config set-context](omqctl_config_set-context.md)	 - Set the active context
* [omqctl config view](omqctl_config_view.md)	 - Display the current configuration


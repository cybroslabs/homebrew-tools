## omqctl config list-contexts

List all available contexts

### Synopsis

The 'config list-contexts' command lists all contexts defined in the configuration file. The active context is marked with an asterisk.

```
omqctl config list-contexts [flags]
```

### Options

```
  -h, --help   help for list-contexts
```

### Options inherited from parent commands

```
      --context string   Context to use for the command (uses the active context if not specified)
  -o, --output string    Output format: console, json (default "console")
  -v, --verbosity int8   Log verbosity level: 0=fatal, 1=panic, 2=dpanic, 3=error, 4=warn, 5=info, 6=debug (default 5)
```

### SEE ALSO

* [omqctl config](omqctl_config.md)	 - Manage omqctl configuration


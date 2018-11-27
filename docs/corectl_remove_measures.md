## corectl remove measures

Removes the specified generic measures in the current app

### Synopsis

Removes the specified generic measures in the current app. Example: corectl remove measures ID-1 ID-2

```
corectl remove measures <measure-id>... [flags]
```

### Options

```
  -h, --help   help for measures
```

### Options inherited from parent commands

```
  -a, --app string               App name including .qvf file ending. If no app is specified a session app is used instead.
  -c, --config string            path/to/config.yml where parameters can be set instead of on the command line
  -e, --engine string            URL to engine (default "localhost:9076")
      --headers stringToString   Headers to use when connecting to qix engine (default [])
      --no-save                  Do not save the app
      --ttl string               Engine session time to live in seconds (default "30")
  -v, --verbose                  Logs extra information
```

### SEE ALSO

* [corectl remove](corectl_remove.md)	 - Remove one or mores generic entities (dimensions, measures, objects) in the app

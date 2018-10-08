## corectl meta

Shows metadata about the app

### Synopsis

Lists tables, fields, associations along with metadata like memory consumption, field cardinality etc

```
corectl meta [flags]
```

### Options

```
  -h, --help   help for meta
```

### Options inherited from parent commands

```
  -a, --app string      App name including .qvf file ending. If no app is specified a session app is used instead.
  -c, --config string   path/to/config.yml where parameters can be set instead of on the command line
  -e, --engine string   URL to engine (default "localhost:9076")
      --ttl string      Engine session time to live (default "30")
  -v, --verbose         Logs extra information
```

### SEE ALSO

* [corectl](corectl.md)	 - 

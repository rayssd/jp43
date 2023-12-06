# JSON Parser for III (JP43)

This bash script trims and prettifies MongoDB "Slow query" logs for better readability.

Dependencies: dprint, jq
```
brew install dprint jq
```

Usage:
```
echo <JSON Log> | jp43
```

or

```
jp43 <JSON Log>
```


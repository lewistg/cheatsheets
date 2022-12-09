# `find`

## Time filters

Files have various time attributes. `Find` has time filter options let us
filter results based on the age of these attributes.

These filter options take the following form:
* `-[time-attribute-filter-option] +n`: Returns file's where the time attribute's age is greater than `n`.
* `-[time-attribute-filter-option] -n`: Returns file's where the time attribute's age is less than `n`.
* `-[time-attribute-filter-option] n`: Returns file's where the time attribute's age is exactly `n`.

Find files modified more than a week ago.
```
find -mtime +7
```

Find files modified less than a week ago.
```
find -mtime -7
```

Find files modified exactly one week ago.
```
find -mtime 7
```



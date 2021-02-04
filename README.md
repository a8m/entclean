# entclean

A CLI for cleaning old ent/schemas

### Install

```
go get -u github.com/a8m/entclean
```

### Examples:

```
entclean User Group

```

Pass custom package path (defaults to "ent"):

```
entclean --path=dir/to/ent Group

```

Skip re-generating assets after clean:
```
entclean --skipgen Group
```


## LICENSE
I am providing code in the repository to you under Apache license. Because this is my personal repository, the license you receive to my code is from me and not my employer (Facebook)

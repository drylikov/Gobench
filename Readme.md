
# gobench

Tiny utility around [benchcmp](https://godoc.org/golang.org/x/tools/cmd/benchcmp).

## Usage

Simple old/new scenario:

```
# benchmark
$ gobench old
$ gobench new

# compare
$ gobench old new
```

Many branches:

```
# benchmark
$ gobench foo
$ gobench bar
$ gobench baz

# compare
$ gobench foo bar
$ gobench foo baz
$ gobench baz bar
```






































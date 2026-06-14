# pepa-spinel

pepa-spinel is a port of [pepa](https://github.com/MarioAriasC/pepa) (The original implementation of the [Monkey Language](https://monkeylang.org) for Ruby) to a compatible Ruby Spinel codebase.

## Status

As of 14 June 2026, Spinel cannot compile pepa-spinel yet.

## Commands

### Testing

Run the command [`mintest`](minitest)

```shell
$ ./minitest tests/*_spec.rb
```

The command also support any minitest option, such as `--verbose` and others

### Benchmarks

#### Ruby 4.0 distribution

You can run the benchmarks with any Ruby 4.0 compatible distribution such as CRuby or JRuby

```shell
$ ruby benchmark.rb
```

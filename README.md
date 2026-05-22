# Synkery CLI

Official command-line interface for Synkery.

This repository is the source of the installable `synkery` command. The main CLI
implementation is expected to live here, with Go as the default implementation
choice for the first usable release.

## Install

```sh
go install github.com/synkery/cli/cmd/synkery@latest
```

## Layout

- `cmd/synkery/` - Go command entry point.
- `internal/` - future Go implementation packages.
- `crates/synkery/` - crates.io placeholder for `cargo install synkery`.
- `npm/` - npm placeholder, future wrapper or installer package.
- `pip/` - PyPI placeholder, future Python wrapper or installer package.
- `install/` - future install scripts.
- `packaging/` - future release packaging.

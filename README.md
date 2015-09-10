# install-go-ipfs shell script

This shell script installs the [go-ipfs](https://github.com/ipfs/go-ipfs) binary.

## Usage

```sh
> install-ipfs.sh [<version>] [<install-path>]
installs the ipfs binary at a local install path
```

## Examples

Install a specific version
```sh
install-ipfs.sh v0.3.7
```

Install to a specific path
```sh
install-ipfs.sh v0.3.7 ./bin/ipfs
```

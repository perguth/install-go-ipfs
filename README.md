# install-go-ipfs shell script

This shell script installs the [go-ipfs](https://github.com/ipfs/go-ipfs) binary. It is not very safe, as it trusts gobuilder to provide a valid binary.

## Install + Run

```sh
wget -q https://raw.githubusercontent.com/ipfs/install-go-ipfs/master/install-ipfs.sh
chmod +x install-ipfs.sh
./install-ipfs.sh
```

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

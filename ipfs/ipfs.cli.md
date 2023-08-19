# ipfs on the CLI

- theres also a desktop app, check the github

## links

- [ipfs cli install: Kubo for go](https://docs.ipfs.tech/install/command-line/#system-requirements)
- [quick start guide](https://docs.ipfs.tech/how-to/command-line-quick-start/#prerequisites)

## basics

```sh
# install via the kubo link up top

# ipfs CMD x y z
init # a repository for the current user
commands # list all commands
daemon # start one, lol but not in daemon mode, maybe theres a flag

# peers
id # query your peer ID on the network
  someOtherPeerId # on the network, e.g. from swarm peers
swarm
  peers # find peers

# working with files
add some/file # POST a file to ipfs, returns digest of content
  -r some/dir # POST a dir recursively to ipfs, returns digest
cat DIGEST # echos content
ls DIGEST # ls content of a directory

## assigning static names to uploaded files
name
  # returns a IPNS_DIGEST: THIS_VERSIONS_DIGEST
  # the IPNS_DIGEST is suppose to alwasys point to the latest version
  # but I couldnt get it load, read the docs whenever you swing back to this
  publish DIGEST

```

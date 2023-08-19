# ipfs

- decentralized storage and p2p media distribution protocol
- a set of composable, peer-to-peer protocols for addressing, routing, and transferring content-addressed data in a decentralized file system
- how you can create a domain name on the ENS (ethereum name service)

## links

- [landing page](https://ipfs.tech/)
- [ENS domains](https://ens.domains/)
- [ipfs github org](https://github.com/ipfs)
- [install steps for bunches of components](https://ipfs.tech/#install)

### browser

- [gateway: view a file on ipfs](https://gateway.ipfs.io/ipfs/<hash-value>)
- [local: web UI](http://localhost:5001/webui)

## Basics

- enables nodes to upload, download and share files with other users in the network
- users need to download and install IPFS on their box
- once users share any type of file on the network

## Architecture

- you should start from the perspective of bittorrent, and expand from there

### Content Based Addressing

- mechanism for storing and managing files uploaded to the network
  - as opposed to location based addressing used by HTTP where data is addressed by its location
  - i.e. ipfs/hashValue vs http://folder/folder/file
- benefits
  - it doesnt matter where a file is located on the network, if you have its hash it can be retrieved

## Web UI

- is available when you start a node

## gateway

- where all ipfs data can be retrieved over http
- files added to ipfs are publically available on the internet

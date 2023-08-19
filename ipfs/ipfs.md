# IPFS: Interplanetary file system

- decentralized storage and p2p media distribution protocol
- a set of composable, peer-to-peer protocols for addressing, routing, and transferring content-addressed data in a decentralized file system
- how you can create a domain name on the ENS (ethereum name service)

## links

- [landing page](https://ipfs.tech/)
- [ENS domains](https://ens.domains/)
- [ipfs github org](https://github.com/ipfs)
- [install steps for bunches of components](https://ipfs.tech/#install)
- [getting started docs: requires daemon running](http://docs.ipfs.tech.ipns.localhost:8080/)

### browser

- [gateway: view a file on ipfs](https://gateway.ipfs.io/ipfs/<hash-value>)
- [local: web UI](http://localhost:5001/webui)

## Basics

- enables nodes to upload, download and share files with other users in the network
- users need to download and install IPFS on their box in order to add files directly
  - retrieve files via its hash value; anywhere on the web over http
- once users share upload type of file on the network its publically available

## Architecture

- you should start from the perspective of bittorrent, and expand from there

### Content Based Addressing

- mechanism for storing and managing files uploaded to the network
  - as opposed to location based addressing used by HTTP where data is addressed by its location
  - i.e. ipfs/hashValue vs http://folder/folder/file
- benefits
  - it doesnt matter where a file is located on the network, if you have its hash it can be retrieved

## Content on IFPS

- appears all basic file types are returned with appropriate mime types
  - check the docs about this when you dive deep

### IPNS: interplanetary naming system

- giving files added to IPFS static addresses that automatically point to their new hash whenever the content changes
- the mechanism is similar to blocks on the block chain
  - each block is linked to the previous block via its hash value
  - each new file version is linked to the previous file version of published on IPFS
    - this is how the static IPNS hash is able to automatically point to the new value
- benefits
  - you can pretty much use this as free website hosting
  - upload a directory, and publish it, then create point a domain to https://gateway.ipfs.io/ipfs/<html-file-hash>

## Web UI

- is available when you start a node
- check the link up top

## gateway

- where all ipfs data can be retrieved over http
  - check the link up top
- files added to ipfs are publically available on the internet

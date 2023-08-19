# ipfs

- decentralized storage and p2p media distribution protocol
- how you can create a domain name in the ENS (ethereum name service) e.g. nirv.eth

## links

- [landing page](https://ipfs.tech/)
- [ENS domains](https://ens.domains/)

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

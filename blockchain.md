# blockchain

- udacitys blockchain course
  - wouldnt trust anything in this repo until i clean it up
  - focusing on finishing up some AWS architecture but need to complete auditing this course before it ends
- Receiver, Transfer and send Funds > Security Best Practices
- todos
  - cleanup these links
  - after auditing the course, you need to run through all of these files and reorganize them
    - e.g. theres a lot of duplicate ish between this and the ethereum verbose file, and likely smart contracts should be in a distinct file

## links

- [how to timestamp a digital document, the first block idea](https://www.anf.es/pdf/Haber_Stornetta.pdf)
- [ethereum NFT docs](https://ethereum.org/en/nft/)
- [consensys incubator and security team for smart contracts](https://consensys.io/diligence/)

### todos

- [AAAA: figure out ethereum storage](https://ethereum.org/en/developers/docs/storage/)
- [bitcoin: peer to peer electornic cash system and PoW](https://bitcoin.org/bitcoin.pdf)
- [anders bitcoin hashing](https://anders.com/blockchain/hash.html)
  - link no longer works
- [anders blockchain block](https://anders.com/blockchain/block)
  - no longer works
- [bitcoin hash wiki](https://en.bitcoin.it/wiki/Hash)
- [cryptographic hash function](https://en.wikipedia.org/wiki/Cryptographic_hash_function)
- [blockchain.com](https://www.blockchain.com/about/index.html)
- [blockchain.com unconfirmed transactions](https://www.blockchain.com/btc/unconfirmed-transactions)
- [blockchain.com charts](https://www.blockchain.com/charts)
- [bitcoin visuals](https://bitcoinvisuals.com/stats)
- [ethereum](https://ethereum.org/)
- [dash](https://www.dash.org/)
- [lisk](https://lisk.io/)
- [ethereum PoS FAQs](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQs)
- [wikipedia proof of stake: block selection methods](https://en.wikipedia.org/wiki/Proof-of-stake)
- [alternative proof of stake methods](https://dailyfintech.com/2016/01/20/why-proof-of-stake-matters-for-blockchain/#content-wrapper)
- [DBFT: neos consensus protocol](https://steemit.com/neo/@basiccrypto/neo-s-consensus-protocol-how-delegated-byzantine-fault-tolerance-works)
- [proof of activity](https://www.coinbureau.com/blockchain/proof-of-activity-explained-hybrid-consensus-algorithm/)
- [proof of burn](https://99bitcoins.com/what-is-proof-of-burn/)
- [neo blockchain](https://neo.org/)
- [multicoin capital](https://multicoin.capital/)
- [electrum](https://electrum.org/#home)
- [getting started with electrum](https://www.youtube.com/watch?v=WdVlH9N2oKU)
- [importing priv keys in electrum](https://bitcoinelectrum.com/importing-your-private-keys-into-electrum/)
- [sweep a private key in electrum](https://bitcoinelectrum.com/sweepi- privatetaddress.org)
- [generate a private key by flipping a coin](https://bitcointalk.org/index.php?topic=297077.msg3197393#msg3197393)
- [generate a private key offline](https://github.com/bigmob/cryptosteel-tutorial/wiki/How-to-generate-private-key-offline-with-Bitaddress)
- [full list of wallets](https://bitcoin.org/en/choose-your-wallet)
- [proof of existence service](https://poex.io/)
- [dappradar](https://dappradar.com/)
- [state of the dapp](https://www.stateofthedapps.com/)
- [trust dapp browser](https://trustwallet.com/dapp)
- [why web 3.0 matters](https://medium.com/@Matzago/why-the-web-3-0-matters-and-you-should-know-about-it-a5851d63c949)
- [understanding web 3.0](https://www.coinbase.com/blog/understanding-web-3-a-user-controlled-internet)
- [blockchain oracles](https://chain.link/education/blockchain-oracles)
- [security: the DAO attack](https://www.coindesk.com/learn/understanding-the-dao-attack/)
- [security: the Parity attack](https://www.coindesk.com/markets/2017/07/19/30-million-ether-reported-stolen-due-to-parity-wallet-breach/)
- [tokens vs coins and creating your own](https://academy.binance.com/en/articles/how-to-create-your-own-cryptocurrency)
- [smart contract security guide](https://scsfg.io/)
- [smart contract attacks whitepaper PDF](https://eprint.iacr.org/2016/1007.pdf)
- [making smart contracts smarter whitepaper PDF](https://eprint.iacr.org/2016/633.pdf)
- [example smart contract vulnerabilities](https://github.com/crytic/not-so-smart-contracts)
- [smart contract bet practices](https://consensys.github.io/smart-contract-best-practices/)
- [smart contract auditing services](https://blog.coinfabrik.com/category/smart-contracts/smart-contract-audit-smart-contracts/)

## terminology

- defi: decentralized finance
- dao: decentralized autonomous organization
- encryption: make a non-reversable secret (laymens), vs encoding (which is reformating)
- hash: a unique fingerprint assigned to a block
  - this is a cryptographic hash, not a hash or checksum
  - any change to the block will require a change to the hash, making the block invalid
  - each block receives a hash value, as well as the hash value of the block that was created before it, hence you get a blockchain
- blockchain data is
  - held, shared and verified by all users on the block
  - anonymous and cryptographically secure
- trusted 3rd party: entity that facilitates interactions between 2 parties
  - establish security to secure, store/record and make transactions
- ledger: list of transaction records, e.g. who sent, received, etc; removes the double spending problem
  - is shared on the blockchain, everyone has access to it
- double spending problem: when someone spends the same money more than once
- wallet address: like an email address

## blockchains

- a shared ledger (db) that records a list of transactions that happen within the network
  - started as an idea by Satoshi Nakamoto back in 2009 to solve problems with financial transactions
  - bitcoin is the first blockchain, but now there are many more
- can be thought of as a type of decentralized database
- public blockchain:
  - permission: open and permissionless design that allows anyone to participate
  - scalability: more difficult
  - vulnerability: less vulnerable
  - compliance: more difficult
- private blockchain:
  - permission: required, and are typically under centralized control
- both private & public
  - depend on a wallet address for identity for transactions and services
  - both keep a public record of transactions that have taken place
  - users can interact autonomously on the blockchain, and others can verify their data
- cross-chain functionality: connecting data across blockchains
  - allows a series of protocols that work in harmony to delivery decentralized applications
  - e.g. a private blockchain can store public blockchain data, like to log bitcoin transactions via their transaction id hash
  - e.g. a public blockchain can store private blockchain data via embedding, e.g. bitcoin core OP_RETURN can store up to 40bytes

### version/generation 1 blockchains

- focused on moving value, maintaining a ledger, and creating ideal payment systems

#### bitcoin core

- the first, but now one of many blockchains
- a type of digital currency that utilizes the blockchain to facilitate financial transactions
- uses blocks to group and validate transactions
- uses sha256 to create a unique hash value for each block on the blockchain

#### litecoin

#### monero

### version/generation 2

- takes many of the lessons learned from first generation blockchains
- focused on recording transactions on the blockchain, adding in programming & logic for associated data via smart contracts

#### Smart Contracts

- a legal contract; programs that perform transactions with the ability to act on acccounts and the data stored in the blockchain
- an event triggers the contract to execute whatever code is held within the contract
- dApps: application whose backend runs on a decentralized network
- consensus
  - arbitration: how are disputes handled; must abide (and think about) laws in the real world
  - transaction validation: all participants required?
  - record immutability: will amend/cancel operations be required?
- data storage: which blockchain to utilize?
  - storing data on the blockchain is expensive, think about DFS protocols like ipfs/swarm/etc
  - can still utilize traditional databases as well
- best practices
  - test test test, unit tests have never been more important
  - remember all execution of code costs money (GAS) and there is a block gas limit that sets the maximum execution time for a smart contract
    - fail fast: you dont want to get half way through some business logic only to fail later in the process
    - business logic should be efficiency, watch out for iterations and logical branches
      - this is a potential lockout scenario if your function cant complete within the gas limit, it wont be able to execute anything else
      - you can externalize loops to the calling program and keep them out of your smart contract

##### Multi-Party Consensus

- enables multisig transactions but at the smart contract (code) level
- still described as M of N
- general logic
  - const M: number of keys required to executed a transaction
  - const N: number of available private keys
    - usually defined indirectly through a set of permitted wallet addresses, e.g. having certain accounts flagged as administrators, or a fixed array of addresses, a function that de/registers a set of accounts, etc etc
  - initialize some counter C on first call of some function requiring the multi-party consensus
    - increment the counter on each subsequent fn call made by distinct administrators, but short circuit until the required threshold is reached
      - make sure the same admin isnt counted more than once
  - basically for some function X, requiring atleast M out of N addresses to agree to allow some transaction, provide some function Y that they can call to cast their vote
    - theres multiple ways to implement this, e.g. consensus achieved within a certain duration, as function modifier, etc etc

#### ethereum

- the first to introduce smart contracts
  - see ethereum doc

#### neo

## blockchain framework

- transaction: a record of information, e.g. who sent it, received, etc
  - are sent to other users and grouped with other transactions into a specific block
  - submitted by users to a node to be included in the next block
  - once the block is filled with enough transactions, it is permanently added to the blockchain
- wallet: contains priv, public keys and address: the addresses are used to send/receive transactions
- digital signature: transactions must be signed by the wallet keys before being sent to the mempool to be included in a block on the blockchain
- mempool (memory pool): where all unconfirmed transactions are placed until mining nodes validate the transaction
- network (distributed P2P network): everyone is able to download a copy of the network data, and work together to achieve consensus to determine which transactions (in the mempool) are valid and should be included in the network ledger
- consensus: a group of algorithms used to create a voting mechanism/process, e.g. PoF, PoS, DBFT
- block: groups transactions and created a single hash for the set
- blockchain: groups of blocks linked via their hashes, contains the entire history of transactions
- hashing: process of generating a digital fingerprint

### state

- how a blockchain manages information within its data storage layer
  - bitcoin state: UTXOs represent the state of the blockchain,
  - ethereum world state: contains bunches of stuff, see docs

### blocks

- the building blocks of the blockchain
- a container that hold a list of transactions to be added to the blockchain
- the blockchain ledger is HUGE, so the blocks provide a way to breakup the long list of transactions into groups of ordered transaction events
- block components
  - body: list of transactions
  - header: block metadata
    - previous blocks hash: the hash value for the block that comes immediately before this one
    - time the block was made: the blockchains solutions to the double-spending problem:
    - merkle root: hash that represents every transaction inside the block
      - pairs of transactions are hashed repeatedly, until youre left with a single hash value
      - can be used to reverse engineer the transaction hash values that made the merkle root
        - you use the hash to search the original transactions (hash values) that created them
        - enables you to find the original transactions that made up the block when starting from merkle root
    - nonce: i.e. number only used once; an arbitrary number that can only be used once
      - block data + nonce = hash value
- block difficulty: the number of 0s requested to make the nonce, the more the 0s the more greater the difficulty
- block size: the amount of space a block has to hold information (e.g. 1mb)
  - is decided by the developer
  - determines how long it takes to create a block, and how many blocks will be on the chain. is the same for every block on the chain, and can only be changed via an update
- block number: identifies the position of this block within the blockchain, i.e. block 1 is the first block
  - genesis block: the block with number 1
- blocks hash value: it includes this blocks data + the hash value of the previous block, creating a chain of blocks (blockchain)

### blockchain

- a shared digital ledger that contains the entire history of transactions made on the network
  - i.e. the transaction history of the network
- a connection of linked blocks joined together by hash values; hash values + blocks are the core components
  - if the hash value of a block is changed, the hash for the next block is also changed, and next block, etc. and all those blocks become invalid
- all information is immutable

### network (distributed p2p network)

- the network enables the blockchain to bypass the need for trusted 3rd parties
- peer to peer: a network of computers that allows information to be shared directly across users (nodes) without the need for a central authority to hold that information
  - enables open communication
- network types
  - centralized network: information is held by a single network owner, and all nodes must connect to it to get information
  - decentralized: information is duplicated and held in multiple locations, and nodes can connect to any of the networks to get information
  - distributed network: a network that duplicates information to each user in the network
    - enables information to be owned by users
    - its a decentralized network pushed to the limits

### mempool (memory pool)

- the waiting place (backlog) for unconfirmed transactions to be verified before they are added to the blockchain
  - the purpose is to provide transaction security
  - transactions must be included in a block, and the block confirmed six times before being added to the blockchain
    - 6 confirmations means 5 additional blocks have been added to that blockchain, then the entire 6 blocks get added to the overall blockchain
    - its considered irrevocable after 6 confirmations, because it will take an considerable amount of CPU resources to revalidate 6 entire blocks
  - transactions sit in RAM (memory) of all the nodes on the bitcoin network
  - six/more confirmations is sufficient proof for a transaction to leave the mempool and be included in a block on the blockchain
  - before a transaction can be considered complete, it must be verified by specialized nodes on the network called miners
- miners: help ensure consensus on the blockchain by verifying transactions in the mempool
- valid reasons for a transaction to leave the mempool (eviction does not imply a transaction is canceled)
  - the transaction expired by timeout (default 14 days after entering)
  - transaction was at the bottom (when sorted by fee per size), the mempool reached its size limit, and a new higher-fee transaction was accepted, evicting the transaction at the bottom
  - the transaction was included in a block (i.e. it shouldnt be in the mempool if it already added to the blockchain)
  - the transaction/one of its unconfirmed ancestors conflicts with a transaction that was already included in a block
- fees: confirming bitcoin transactions requires a lot of computational memory,
  - everytime a sender puts out a transaction into the mempool, they add a transaction fee, a tip for the miner to validate the transaction
  - miners can look through all possible transactions and will pick the one with the higest fee, (thats how they get paid)

### consensus

- drives all the decisions made to establish and grow the blockchain; its how the blockchain makes decisions; and how blocks join the blockchain
- a voting process for the network, that makes decisions about information on the blockchain, e.g. which transactions are most trustworthy
- byzantine generals problem: an analogy for a distributed network and reaching consensus amongst nodes
  - 9 generals encircling an army, need to make a decision about how best to attack, or retreat, and all nine must agree to do the same thing, else they will lose
  - of the 9 generals, there could be some who are traitors (word to malcolm X)
  - the generals are physically separated, and must send their votes via messengers, which could be attacked along the way, lose the msg, or change the msg

#### proof of work (PoW)

- summary: miner nodes solve a math puzzle that requires a lot of computation power. whichever miner is able to solve the puzzle the fastest is able to add a block of transactions to the blockchain
  - in return, they are paid the transaction fees from all the transactions included in the block, as well as paid by the netowrk with bitcoins that were newly created upon the mining of the block
- bitcoin uses PoW
- a way to achieve consensus without a centralized authority, original proposed by bitcoin (see the paper link)
- whoever puts in the most work to contribute to the system is the most trustworthy
  - a system where information can be costly to produce (the work required to generate a blocks hash value), but easy to verify
  - each node is involved in solving a problem to prove theyve done the required work
  - solving the problem (takes a long time) is indicator/signal that the node can be trusted
    - the problem is finding the Nonce for the next block
  - the nodes that solve the problem are known as miners
    - miners are in a race with eachother to solve the next problem, in order to be the one that puts the next block on the blockchain
    - in return for their time and resources they are paid transaction fees (by the users) and in bitcoin (by the network)
      - the bitcoin is created specifically for miners, and is the only way new coins are added to the network
- the proof of work requires a certain type of hash value, that starts with a certain amount of zeros (this is the block difficulty)
  - you get the zeros by having the correct Nonce + block data
  - since the block data (the transactions) arent changing, the only option is to change the Nonce
  - guessing the Nonce is time consuming, and the more leading zeros required in the final hash value, the longer the guessing game takes
  - bitcoin adjusts the block difficulty (amount of zeros required) to ensure a new block is created every 10 minutes
    - 10 minutes was arbitrarily decided by the bitcoin developers, as a balance between network security and efficiency of creating new blocks
      - too fast: hackers can attempt to change the data
      - too slow: network cant keep up with the amount of transactions happening and the mempool will be overloaded
- issues
  - extremely high energy consumption: the compute power to calculate the correct Nonce is super high
    - mining rigs/farms are setup that consume a lot of energy
  - monopoly of miners leads to concern for centralization
    - those who have the resources to access more equipment have an unfair advantage
    - they have more say in which blocks are considered valid

#### proof of stake algorithm (PoS)

- summary: there are no miners, instead validators (stakeholders) determine which block makes it onto the chain
  - bad delegates: users may not know which other nodes are good, and be unable to cast meaningful votes
    - solution: some platforms release data about the honesty and put up their own coins as stake, like placing a bet
  - if they validate a fraudulent transaction, they lose their stake as well as their rights to participate as a validator in the future
- who uses it
  - ethereum uses PoS (but use to be use PoW)
  - DASH: pioneer of PoS: built from the core bitcoin platform with added features for privacy and Tx speed
    - PrivateSend: todo
    - InstantSend: todo
  - LISK: focused on creating decentralize Apps; uses delegated PoS
    - dapps are built with javascript
    - delegated PoS: only the top 101 delegates are able to have stakes in the network
      - delegates are voted on in a rolling basis by the community; 1 Lisk === 1 vote
- focuses on giving votes to members, depending on how much stake they have in the success of the chain; more stake === more votes
- validators: aka stakeholders: determine which blocks make it onto the blockchain
  - validators put up their own coins as stake, as if they were placing a bet
  - if a validator puts an invalid transaction into a block on the blockchain, they lose their holds and their right to participate as a validator in the future
    - this incentives validators to validate only truthy transactions
    - the greater the % of total coins a validator owns, the higher the chance of them being picked of validating the next block
    - if a validators block is added to the blockchain, they are added coin proportional to the amount of their stake
  - there are no miners in PoS that mine coins, because all the coins already exist
- forks: TODO
  - basically when there are multiple proposed blocks and that leads to a split, need to research this some more
- issues
  - nothing at stake problem: if a validator bets on multiple blocks, so they always win.
    - slasher solution: validators are penalized if they simutaneously create blocks on multiple chains
    - other solution: validators are penalized for creating blocks on the wrong chain; forcing them to be selective about which blockchain to put their stake on

#### delegated proof of stake

#### delegated Byzantine fault tolerance (DBFT) algorithm

- summary: ordinary nodes in the system vote on representative delegate nodes; the delegate nodes decide which blocks should be added to the blockchain
  - when its time to add a block, a randomly selected delegate is selected as speaker, proposes the block of transactions to add, and atleast 66% of the other delegates must approve, the process repeates if less than 66% (2/3rds) fail to approve the proposed block
- neo uses DBFT
- said to be much faster that PoW because there are no complicated cryptographic puzzles to solve
- there are no forks: because there is always only one version of truth
  - due to the consensus nodes + voting process
- assignes roles to nodes to help coordinate consensus
- does not have miners, but instead consensus nodes and regular nodes
  - regular nodes: just normal users
  - consensus nodes: have the power to verify each block written to the blockchain; act as representatives for other nodes in the network
    - keep track of proposed blocks that could be added to the blockchain
    - when its time to add a block to the blockchain, a random consensus node is selected,
      - NEO blockchain: labels the selected consensus node SPEAKER, and the others delegates
        - the speaker creates a new block and proposes it to the delegates
        - 2/3rds of delegates must approve the block, else a new randomly selected consensus node becomes speaker and the process repeates
- issues
  - bad speaker: since speakers are chosen randomly, the selected speaker could be dishonest/malfunction
    - solution: since users vote on delegates, and delegates are randomly selected to become speaker, its up to the users to ensure only honest nodes become delegates
      - haha dumb fkn people problem!
  - bad delegates: users may not know which other nodes are good, and be unable to cast meaningful votes
    - solution: some platforms release data about the honesty and functioning of each delegate for voters to review
      - haha! dumb fkn people problem!

#### Proof of Activity

#### proof of elapsed time

#### proof of burn

### transactions

- the fundamental building blocks of any blockchain
- a data structure that encodes a transfer of value from a source of funds (input) to a destination of funds (output)
  - the wallet needs to have enough funds, the sum of the input transactions + fees
- transactions start broadcasting to the network when a wallet first signs a transaction
  - a signature is required before a transaction is submitted to the network
  - you sign the transaction via the private key linked to your wallet address
  - the signed transaction goes from the sender to the receiver as a transaction message
  - can be made up of multiple transaction inputs and outputs
    - e.g. a single input will generally require two outputs, input to cover the value being transferred + miner fees, 1 output to the receiver, 1 output as change back to the sender
- transaction inputs:
  - all inputs are unspent outputs from another transaction, i.e. all inputs reference back to an output, e.g. the initial funding of a wallet
  - conditions: transaction inputs need to be converted to an output, which contains the condition to prove ownership using a private key
- transaction output: aka UTXO; the amount received by a wallet in a transaction
  - UTXO: unspent transaction output; the initial broadcast of a transaction to the network; only UTXO messages can be used as inputs to an accepted transaction
    - contains conditions (proofs): proof of ownership to transact with those funds (derived from the wallet addresses private key)
    - is indivisible, like a coin, cant be cut in half,
      - if the value of a UTXO is larger than the desired value of a transaction, it must still be consumed in its entired, and an additional output must be created to give change back to the owner
  - when a user receives bitcoin, that amount is recorded on the blockchain as unspent outputs (UTXO);
  - all of a wallets UTXO is scattered throughout the blockchain
  - when its time for them to spend that bitcoin, the wallet scans the blockchain and aggregates all the UTXO belonging to that user, and calculates the balance
    - i.e. theres no such thing as a stored balance for an account/bitcoin address; theres just a bunch of UTXO scattered on the blockchain, all linking back to a specific wallet address
- lifecycle 1
  - get the receivers wallet address
  - create a transaction: amount to send + transaction fee
  - verify & sign the transaction via senders wallet, using the wallets private key
  - broadcast the transaction to the mempool
  - miners eventually accept the transaction, group it into a block, find the proof of work, and assign the block a hash value
  - the block is eventually placed onto the blockchain
  - as the block gains confirmations, its eventually accepted as a valid transaction
  - the receiver finally receives their funds
- lifecycle 2
  - i want to send 2 bitcoin
  - wallet scans the blockchain and retrieves two UTXO belonging to my address that can be summed to cover the costs
  - these two UTXO becomes input to a new transaction, and the change is converted to an output (another UTXO) and linked back to my wallet address

### wallet

- establishes your identity on the blockchain
  - when you move crypto from one address to another, you need to provide a digital signature proving that you control/own that address, i.e. your signing a transaction that shows you control the address from which the crypto is moving from
- restoring a wallet
  - use a seed: the 12 words used to initially create the wallet
  - import a private key: you take the private key of a source wallet and import it into a destination wallet
    - enables you to access the key via the source/destination wallet(s)
      - be careful, as now the source wallet has been shared, it increases the likelihood of being compromised
  - sweep a private key: move the private key of a source wallet into a destination wallet
    - the source wallet is now empty, and the destination becomes the new source

#### keys

- private > public > wallet

##### private keys

- private key: a cryptographically secure randomly generated number that allows you to send crypto from your wallet; everytime you interact with the blockchain, you have to sign that transaction with your private key
- formats:
  - hexadecimal: 256 bits === 32 bytes
  - wallet import format (WIF): make it easier to make different copies for different use cases
    - WIF (Base58Check):
    - WIF-Compressed (Base58Check added suffix 0x01 before encoding)
- generating
  - find a secure source of entropy to make it random/unpredictable

###### Multi-Signature Accounts (multisig)

- i.e accounts that have multiple private keys
  - e.g. avaliable on the bitcoin blockchain
  - ethereum uses multi-party consensus instead
- similar to how hashicorp vault requires multiple keys to unlock the vault db
- described as M of N accounts,
  - M the number of required keys for a transaction
  - N the total number of keys available
- benefits
  - prevents thefts of funds, since multisig accounts requires multiple keys to sign transactions, no single key will put the entire account at risk
  - prevents loss of a single key
  - enables business rules for arbitrary types of transactions, e.g. based on total amount may require different amount of keys

##### public key

- public key: a shareable key that cannot be used to spend crypto; but used to receive crypto; created from the private key via some one-way elliptic curge digital signature algo (ECDSA see security docs for indepth);

##### wallet address

- wallet address: a unique identifer made from the public key for a wallet that can be shared with anyone

#### non deterministic wallet

- random wallets where private keys are generated from random private keys as seeds (instead of easy to remember words)
  - random number > priv key > pub key > wallet addrss
  - nothing can be traced back to the random number
- best practices
  - generate a new wallet address for each transaction, so no one can trck links between addresses
  - make sure to backup the wallet, so you dont lose the generated priv key
- use cases
  - backend services

#### deterministic wallets

- all priv, publick and wallet addresses can be traced back to the original seeds, theres a purpose behind each

##### sequential deterministic wallet

- derived sequentially from a single seed and can be traced back to that seed
  - a random number is used to generate a seed (e.g. 12 words)
  - the seed is put through an algo to create a private master key
  - the private master key goes through an algo, to create a new private key, and so on
  - the seed can be used to regenerate everything as well as export/import to migrate the wallet to diferent impelmentations, thus only a single backup is necessary
- first introduced in electrum

##### hierarchical deterministic (HD) wallet

- borne from the bitcoin improvement proposal 32 (BIP32)
  - BIPs are used to improve the bitcoin proposal
- an advanced type of deterministic wallet that contains keys derived in a tree structure
  - a seed creates a master key
  - that master key can create child private/public keys, chlid keys can create grandchild private/public keys, and so on
- seed words: list of words that store all te information needed to recover a wallet
- use cases
  - businesses that want to separate out different departmental spending
    - since all the keys still tie back to the initial master key, you can still assert authority over all public/private ancestor keys
  - assigning keys to application users that need to be paid
  - creating keys for different types of transactions
  - trustless servers: a webserver can create ancestor public keys for various tasks, and never share the private key
- best practices
  - the master key must be secured, as everything falls apart if its leaks

### privacy

- various cryptographic algorithms to maintain privacy

#### Hashing

- hash function: any function that can be used to map data of arbitrary size to fixed-size values, though there are some hash functions that support variable length output.
- hash values: the values returned by a hash function
  - usually used to index a fixed-size table called a hash table. Use of a hash function to index a hash table is called hashing or scatter storage addressing.
- cryptographic hash function: uses cryptography to generate a hash value thats difficult to reverse engineer or generate using a different input
- blockchain hashing logic
  - generate private key
  - hash private key with ECDSA to create public key
  - hash public key with SHA256, then with primitive to digest (RIPEMD-160) to create a public key hash
  - make the wallet address via Base58Check
- privacy issues with hashing
  - if you simply hash and commit transactions to the blockchain, eavesdropper wont be able to know the hash input, but will still be able to see the level of activity
- positives
  - entities can safely conceal and send data to each other, as well as verify the data hasnt been tampered with by recomputing the hash digest and comparing

#### Merkle Trees

- overcomes the privacy issues of hashing by concealing the number of hashes committed
- general algorithm
  - the input is a set of values
  - compute the hash for each value in the set
  - recursively combine and compute the hash for each pair of hashes until a single hash remains, creating a sort of balanced tree
    - if you have an odd number of hash values, duplicate the last one
  - the final hash is the merkle root
  - commit the merkle root to the blockchain
- merkle proof: the minimum number of hashes that make up the merkle root required to determine if some hash X is indeed part of the merkle root
  - the merkle proof for some hash X is all the hashes used to include hash X into the merkle root in the recursive hashing computation step
  - this enables entities to validate hash X is indeed part of the merkle root that was committed to the blockchain without requiring every hashed used in the merkle root
- positives
  - merkle trees summarizes all the transactions in a blockchain block and produces a digital fingerprint of all the transactions enabling entities to verify individual transactions are indeed included in a block

#### digital signatures

- all blockchains use
  - assymetric (public-key) encryption for wallets
    - public key: encrypt data
      - you get the public key of an entity, encrypt data, and send it to them
    - private key: decrypt data
      - only the private key can decrypt data, never share this
  - hash fns for data integrity
- establishes a proof of ownership for each transaction on the blockchain
- created via the wallet address
- before the blockchain accepts a transaction, it must be signed
- privacy issues
  - if you know who owns the public key to some signature, then you know who owns that data

#### Zero-knowledge proofs

- zero knowledge: the entity your proving to doesnt learn anything more than the bare fact you're proving
- zero knowledge interactive proof: proving a fact by repeated computations until the entity you're proving to is satisfied, but without revealing the actualy algorithm
  - generally only useful in scenarios where entities actively take part in the computation, as internal entities could be acting in coordination to fool observers
- zero knowledge non-interactive proof: proofs where the secret holder can create a proof without relying on anyone else

##### ring signatures

- zero knowledge proofs of set membership
  - an entity can proove they own a public key part of ring set, without revealing which specific key
- overcomes the privacy issue of assymetric signatures by validaing against a set of public keys instead of a specific public key
- simple explanation of algorithm
  - combines a set of public keys into a list (aka ring)
  - when it is time to verify some piece of data, it is checked against all keys in the ring
  - if at least one key was used to sign the data, its considered valid
  - and if the same key signs different messages, you can verify it was signed by the same key

##### ZK-SNARKS

- simple explanation
  - prove to an entity that you have the input to a computed value (e.g. a hashs input) with cryptographic certainty without you revealing the underlying computation or what the input is
  - a way to prove something non-interactively, in a cryptographically secure fashion
- an acronym someone somewhere is really proud of
  - ZK: zero knowledge; prooving something without revealing anything more
  - S: succint; in terms of data, the size of the proof generated relative to the size of the knowledge you claim to possess, is minimal
    - important in environments where data storage is expensive, e.g. on the blockchain
  - N: non interactive; sufficient proof for everyone
  - AR: arguments; i.e. the stuff you provide to prove the proof, probably should google this as aaron's explanation wasnt that intuitive
  - K: the knowledge you're trying to prove you have
- cryptogrpaphic circuit: a program that accepts a hash from entity A, and some data from entity B, computes the digest from empty B's data and compares it to the digest received from entity A
  - this enables entity B to prove to entity A that it has the secret data, without revealing what that data is
  - entity B cannot change the cryptographic circuit without entity A knowing about it, so entity A trusts entity B indeed has the data that created its hash

#### Differential Privacy

- a set of techniques used to maximize both the usefulness of a dataset as well as the privacy of individuals within that dataset
  - overcomes the competing goals of companies needing identifiable data, and users needing their privacy
  - enables a company to learn general patterns of behavior about a group of participants without knowing details of any specific user
- this is different than just anonymizing/de-identifying PII
- general process involves a bunch of statistical methods, but as an example:
  - data collectors apply random noise to the dataset before providing it to data consumers
    - this random noise makes specific users data untrustable
    - since the data collectors know the amount of random noise introduced, they can still provide useful statistics to consumers

### digital assets

- digitally stored content/online account owned by an individual
  - blockchains help with ownership of digital assets, but not storage,
    - see proof of existence elseware
    - instead of who owns this transaction, the blockchain answers who owns this asset
- compression algorithms: goal is to make something smaller
- encoding: process of putting a sequence of chars into a specialized (raw) format for efficient transmission between computers or storage
  - ASCII: (pronounced asky, or ass-kee) american standard code for information interchange; based on the idea that you can represent text as numbers
  - Base64: more concise and human redable representation of binary;
  - Hexadecimal: encoding scheme meant to represent data as numbers in a string format; 0-9 and a-f; use xxd on the cmd line
- decoding: takes encoded, raw, unreadable files and converts them back into human readable format
  - uses the same encoding schemes

#### Proof Of Existence (POE)

- a concept & service that publicly proves and authenticates any digital asset on the blockchain by verifying its hash, e.g. via SHA256/MD5
- its like a notary service
- verification: check the integrity of the digital asset to confirm that it contains the correct sequence of byts and has not been wrongfully accessed/altered
  - doesnt refer to the trustworthiness of the source file, only that it hasnt been tampered with
  - only the hash of the digital asset is stored on the blockchain, but not the asset itself
  - the hash is linked to the time the document was submitted, so even the time of ownership can be proven
    - this way even ownership of private assets can be proved
- example steps
  - digital asset is hashed via sha256
  - the hash is appended to an identifier
  - the hash + idnetifier is put into a generated transaction
  - the transaction is marked with OP_RETURN so its unspendable
- use cases:
  - data ownership: e.g. copyrights, patents, etc, when encoding the tx on the blockchain, you can include the owners identity
  - integrity checks: validate an asset hasnt changed
  - time stamping: prove some asset/info existed at a certain time
  - certifies the existence of an asset without the need for a central authority
  - secure an asset: protect an asset from wrongful access/alteration

#### Non Fungible Tokens (NFTs)

- non fungible: an economic term you could use to describe things like furniture, a song file, etc; things that arent exchangable for other items because they have unique properties
- can only have one official owner (based on their private key) at a time
  - similar to how you sign messages with a private key to prove you created the msg,
  - however there is a way to create fractional/shared ownership
    - e.g to give others oportunities to own a part of an NFT without having to buy the whole thing
- the creators public key serves as a certificate of authenticity for that digital Artifact
  - i.e. its a permanent part of the tokens history, and proves the NFT was created by the creator and not a counterfeit
- use cases
  - a way to represent anything unique (and original) as a blockchain-based asset, e.g. a deed for an item in the digital or physical realm
    - tokenise things like art, collectives, real estate, etc.
  - digital reprelicate properties of physical items like scarcity, uniqueness and proof of ownership
  - commerce: creators can sell, and when items resell can claim resell royalties directly
  - debt: use items as collateral in a decentralised loan
- scarcity: creator decides how many NFT (i.e. tokens) exist
  - e.g. 500 tickets to a concert, 1 art piece
- royalties: some NFTs automatically pay out royalties to their creators (e.g. foundation.app, zora.co)

### Security

- remember:
  - large amounts of money are involved in transactions that anyone can access
  - smart contracts cant be updated after launch: they are eternal and P2P
    - however you can pause them so no further transactions are processed, see stop loss section
- auditing questions
  - what vulnerabilities may be latent in the contract logic
  - how might someone discover these vulnerabilities
  - if found, how would someone exploit each vulnerability
  - what needs to be changed to remove and guard against these issues

#### Stop Loss

- business case
  - since you cant update a contract (i.e. change its terms) once its been deployed
    - imagine being able to change the terms of a contract in the real world after all parties agreed on it! doh!
  - the contract owner can instead pause the contract by changing its state
- general logic
  - add a boolean variable that determines the state of the contract
  - add a function that enables the contract owner to update the state variable
  - add a function modifier with require() that references the variable and short circuits based on its current value
    - a helper modifier fn should be applied to all functions that change state to shortcircuit based on the current state
      - FYI: be careful not to introduce any `Lockout Bugs` whereby the owner gets locked out of updating the state variable because its in a falsy state

### Case Studies

#### the DAO Attack

- accounted for the loss of around 60 million dollars worth of Ethereum
- business case
  - the smart contract was like venture capital fund: allowing users to donate to causes they deem worthy
- core logic
  - enables users to donate coins to some address
  - allows users to withdraw previously donated coins
- the vulnerability
  - in the ether docs its called `Re-Entrancy`
  - the Fundraiser code that enabled a user to withdraw previously donated coins didnt account for how a wallet will interact with the contract
    - when the Fundraiser contract called the payout function, it was delegated to the contributing wallet's payout function
      - the contributing wallet called payout() BEFORE the Fundraiser contract ZEROED the donated balance
- the hack
  - since payout() is called before the donated balanced is ZEROED
  - the contributing wallets payout function was changed to recursively call withdraw() before returning to the Fundraiser contract
  - hence draining the contract for ALL coins donated and NOT just the contributing wallets donated balance
- the fix
  - moving the line that ZEROED the contributing wallets balance BEFORE the payout logic begins
  - now if the payout function is recursively called, they will receive 0 coin since the donated balance has been zeroed

#### the Parity Attack

- resulted in many millions of dollars in lost Ethereum
- business case
  - parity wallet provided a library contract that helped other users create wallets
  - the goal was to provide base logic reusable in any wallet
- core logic
  - delegate calls: enables contract A to call functions from contract B
  - fallback function: all contracts can contain a single anonymous function that acts as the fallback whenever an undeclared function is invoked
    - e.g. contract A calls fn iDontExist in contract B, contract B will invoke its fallback function
- the vulnerability
  - the way the library was setup to initialize and add a wallet owner was invalid based on delegate calls and fallback funtions
- the hack
  - user A deployed a contract based on the invalid library
  - now when user B utilized the malicious contract it made a call to a function that doesnt exist, and when the delegate call invokes the fullback function, the malicious contract called addOwner to change the contract owner from user B to user A
  - user A then fk uped user B's whole summer
    - and this happened to every user who created a contract utilizing the invalid library
- the fix

## Web 3.0

- web 1: the birth of the internet
- web 2: dominated by large players
  - doesnt hold state: you cannot inspect the history of connected devices
  - doesnt transfer state: large centralized services control the bit of state that exists and the value it providers
  - cookies: controlled by service providers, not the users
- web 3: allows the internet to hold and transfer state and the value state provides
  - gives the power to the users/creators instead of centralized into large corps

### Architectural Components

- wallet: the core mechanism through which users interact with web3 applications
  - manage their private keys and sign transactions
  - interact with the frontend that connects to a blockchain server
- blockchain server: middle man between a frontend client (wallet/another server) and the blockchain network
  - blockchain node provider
- decentralized storage

#### Modeling Blockchain Solutions

- Assets: Any physical or digital entity that requires tracking
- Attributes: anything of interest: asset (what), ownership (who), time (when), and location (where)
- Business Process: Progression of assets through various steps of a business process recorded for trail of evidence.
  - Smart contracts enforce the business process on chain curbing rogue actions
- Business Actions: User or machine initiated actions that allows assets to progress from one process state to the next
- Actors: Users that interact with the asset to perform process actions and transform the asset from one state to next.
  - Users that have ownership or custody of the asset.
  - Users that participate in audit, review and attestation of the asset to validate history.
- Role Permissions: Permissions to perform business actions are assigned by roles.
  - The web interface and smart contracts enforce the permissions, preventing rogue users from tampering

#### Development Components

- code editor: e.g. vscode or remix-ide
- development framework: e.g. truffle for ethereum to develop, test and deploy dApps to an ethereum node
- development node: you need a sandbox for testing dApps
  - e.g. ethereum requires an ethereum node, and has tools to create local nodes like Infura
- storage: if going blockchain native use a DFS protocol like ipfs/ether swarm
- browser: access dApps via browser extensions like metamask or using brave (i think)

### Decentralized File System (DFS)

- aims to replace HTTP protocol
  - how computers format and transmit information over the web
  - embraces blockchain principles like decentralization and p2p networks
  - moving ownership of data into the hands of users that generate it, instead of centralized ownership by big tech companies like AWS, google and dropbox
- used in coordination with dApps, to create fully decentralized applications
  - dApps: decentralization computation via blockchain
  - dfs: decentralized, distributed storage

## Use cases

- remember the blockchain is simply a distributed ledger for tracking stuff
- you can utilize the blockchain as a database for any thing that needs to be tracked and verified by participants in a process
- a big plus if there is money being moved around, as you can eliminate third parties (sorry banks!)

### Supply Chain Management

- everything needed to plan, build, create, manufacture and deliver a product to different types of customers
  - all the processes involved with the production and distribution of a commodity.
- the goal is to streamline a distributed and complicated process, building trust between suppliers and partners and automation of contracts and negotiations throughough every step
- benefits of smart contracts
  - transparency
  - tracability
  - efficiency

### Finance

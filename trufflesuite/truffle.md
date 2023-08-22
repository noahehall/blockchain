# Truffle Suite

- smart contract development
- https://trufflesuite.com/docs/truffle/how-to/truffle-with-metamask/#using-metamask-with-ganache

## links

- [landing page](https://trufflesuite.com/)
- [docs landing page](https://trufflesuite.com/docs/)
- [install steps](https://trufflesuite.com/docs/truffle/how-to/install/)
- [ethereum client](https://trufflesuite.com/docs/truffle/concepts/ethereum-client-types/)
- [Truffle boxes](https://trufflesuite.com/boxes/)

### ecosystem

- [@truffle/contract](https://github.com/trufflesuite/truffle/tree/develop/packages/contract)

### docs

- [contracts: how to](https://trufflesuite.com/docs/truffle/how-to/contracts/interact-with-your-contracts/)
- [migrations: how to](https://trufflesuite.com/docs/truffle/how-to/contracts/run-migrations/)
- [tests: how to](https://trufflesuite.com/docs/truffle/how-to/debug-test/test-your-contracts/)
- [configuration: how to](https://trufflesuite.com/docs/truffle/reference/configuration/)
- [dashboard: how to](https://trufflesuite.com/docs/truffle/how-to/use-the-truffle-dashboard/)

### boxes

- [webpack](https://trufflesuite.com/boxes/webpack/)

## basics

- You need to run most Truffle commands against an existing Truffle project

```sh
nvm use 18
npm i -g truffle
truffle version # verify it all works
npm i -g ganache

## quick cmds
truffle CMD x y z

init # a barebones project
unbox BOXNAME DIRNAME # use BOXNAME template

test # all files in test dir
compile # incrementally all files in contracts dir to the build dir
  -all # force compile
migrate # deploy compiled files to the blockchain

develop # spin up a basic ganache instance and connects a console to it
console # connects to the blockchain specified in config.network
dashboard # deploy to alternative networks


```

### Directory Hierarchy

- build: output dir
  - contracts: compiled
- contracts: for solidity contracts
- migrations: for scriptable deployment files
- tests: for tests

### Configuration

- root/truffle-config.js

```jsonc
{
  "networks": {
    "development": {
      // points to a standalone ganache instance
      "host": "127.0.0.1",
      "port": 7545,
      "network_id": "*"
    }
  }
}
```

## boxes

- boilerplates for different kinds of dApps

## compiling

## Testing

- truffle tests can be written in typescript

## ecosystem

### @truffle/contract

- npm package for interacting with contracts in a browser

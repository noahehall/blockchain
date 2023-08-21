# Truffle Suite

- smart contract development
- bookmark: https://trufflesuite.com/docs/truffle/how-to/create-a-project/

## links

- [landing page](https://trufflesuite.com/)
- [docs landing page](https://trufflesuite.com/docs/)
- [install steps](https://trufflesuite.com/docs/truffle/how-to/install/)
- [ethereum client](https://trufflesuite.com/docs/truffle/concepts/ethereum-client-types/)
- [Truffle boxes](https://trufflesuite.com/boxes/)

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

truffle
  test # all files in test dir
  compile # all files in contracts dir to the build dir
  migrate # deploy compiled files to the blockchain
  develop # spin up a basic ganache instance and connects a console to it
  console # connects to the blockchain specified in config.network
  dashboard # deploy to alternative networks

```

### Configuration

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

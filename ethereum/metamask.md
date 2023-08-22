# matamask

- browser wallet & tool for interacting with ethereum dapps directly in the browser without running a full ethereum node
  - works as an injected web3 provider
    - it injects web3 into the browser so dApps can use it,
    - also makes a node available
  - users need to have metamask installed in their browser to for your dapp to work

## links

- [landing page](https://metamask.io/)
- [docs](https://docs.metamask.io/)
- [how to guides](https://docs.metamask.io/wallet/how-to/)

### faucets

- [public faucet](https://faucet.metamask.io/)
- [rinkeby facuet](https://faucet.rinkeby.io/)

### docs

- [introduction](https://docs.metamask.io/wallet/)

## basics

## ecosystem

### remix integration

- any changes to your metamask config will generally require you to redeploy your smart contract within remix
  - this is because remix connects to metamask, so if you change what blockchain metamask is connected to, you'll have to redeploy the contract to that new blockchain (e.g ganache) and update any downstream code with the new contract address (provided by remix)

### truffle integration

- recommended to also use @truffle/contract npm package

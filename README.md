# Onchain NFT example

Contract address: [0x3AEDBc554Af1977034c3FFeD00251ab18935F5Ce](https://rinkeby.etherscan.io/token/0x3AEDBc554Af1977034c3FFeD00251ab18935F5Ce)

## Local development

1. Launch a local node

```sh
pnpm node
```

2. Deploy contract on local testnet

```sh
pnpm deploy
```

3. Use contract in console

```sh
pnpx hardhat console

> const Greeter = await ethers.getContractFactory('Greeter')
> const greeter = Greeter.attach(`...`)
> greeter.setGreeting('hello')
```

# Onchain NFT example

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
# contract-issue-193

## init the project

follow the document in https://docs.polkadot.com/tutorials/smart-contracts/launch-your-first-project/test-and-deploy-with-hardhat/

## configure the passetHub in hardhat.config.ts

## store private key into hardhat env

```shell
npx hardhat vars set PRIVATE_KEY "0x"
```

## compile

```shell
npx hardhat compile
```

## deploy

```shell
npx hardhat ignition deploy ignition/modules/MyToken.ts --network passetHub
```

## test

```shell
npx hardhat test test/MyToken.ts --network passetHub
```

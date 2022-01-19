This is test NFT using 

https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/

1. Compile contract

```
npx hardhat compile
```

1. Deploy Contract

```
npx hardhat --network rinkeby  run scripts/deploy.js --verbose
```

1. Record contract address in .env

1. Mint the NFT

```
node scripts/mint-nft.js
```
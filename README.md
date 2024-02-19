# Musing
Decentralized and Tokenized Communities Online - [Musing](https://musing.io)

## Run Tests
```bash
npx hardhat test
```

## Deploy
```bash
npx hardhat compile

HARDHAT_NETWORK=bscmain node scripts/initial-deploy.js

# Verify source code on Etherscan
npx hardhat verify --network bscmain {contract address} "parameter 1" "parameter 2"
```

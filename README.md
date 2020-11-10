# MetaCoin Truffle Box

MetaCoin example Truffle project

## Installation

```
git clone https://github.com/harmony-one/metacoin-box.git && cd metacoin-box
yarn install
```

## Deployment

### Initializes environment variables
1. copy `.env.expample` to `.env`, and change the priveate key/mnemonic to yours.
2. excute `source .env`

### Compile contract

run `truffle compile`

### Deploy to Testnet

run `truffle --network=testnet deploy --skip-dry-run`

### Deploy to Mainnet

run `truffle --network=mainnet0 deploy --skip-dry-run`
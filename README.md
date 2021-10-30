# hardhat-tutorial

This repository contains the project developed in [Hardhat's tutorial](https://hardhat.org/tutorial/). There's also a version that includes a minimal frontend [here](https://github.com/nomiclabs/hardhat-hackathon-boilerplate).

## Development

### Requirements

- Node 16;

### Setup

```sh
git clone https://github.com/umluizlima/hardhat-tutorial.git
cd hardhat-tutorial
npm install
```

### Test

```sh
npx hardhat test
```

### Deploy to Ropsten testnet

```sh
npx hardhat run scripts/deploy.js --network ropsten
```

## Dependencies

- [Hardhat](https://hardhat.org/): An Ethereum development task runner and testing network.
- [Mocha](https://mochajs.org/): A JavaScript test runner.
- [Chai](https://www.chaijs.com/): A JavaScript assertion library.
- [ethers.js](https://docs.ethers.io/ethers.js/html/): A JavaScript library for interacting with Ethereum.
- [Waffle](https://github.com/EthWorks/Waffle/): To have Ethereum-specific Chai assertions/mathers.

## Utilities

- [nvm](https://github.com/nvm-sh/nvm): Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions.
- [editorconfig](https://editorconfig.org/): EditorConfig helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.

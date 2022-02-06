# Ethereum Dapp for Tracking Items through Supply Chain

This project was developed as part of the [Udacity Blockchain Developer Nanodegree Program](https://www.udacity.com/course/blockchain-developer-nanodegree--nd1309)

This projects contains an Ethereum DApp with a Coffee Supply Chain flow between a Farmer, Distributor,
 Retailer and Consumer. 
- A Farmer can harvest, process, pack, and sell items.

- A Distributor can buy and ship items. 
- A Retailer can receive items
- A Consumer can purchase items.

## Rinkeby test network

This contract is deployed to the Rinkeby test network:

Contract Address: [0x7d391e68341066e11b916dd7c88392665735ff32](https://rinkeby.etherscan.io/address/0x7d391e68341066e11b916dd7c88392665735ff32)

## Project Diagrams:
Activity, State, Sequence, and Data model diagrams can be found in the [diagrams folder](diagrams)

## Libraries:

- Node v10.24.1
- Truffle v4.1.14
- Solidity v0.4.24

## Local development

1. Run `truffle develop` to start you local blockchain
2. Inside truffle run `migrate --reset` to deploy the contracts
3. To start the frontend run `npm run dev` in a new terminal


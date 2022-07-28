# Blockchain Runner Game
![](https://github.com/sejalxz/runner-game/blob/main/runner-game.gif)

## [Click to Play Runner Game](https://sejalxz.github.io/runner-game/)

This project is a Blockchain game that uses [OpenZepplin](https://github.com/OpenZeppelin/openzeppelin-solidity).

The contract is compiled and deployed under the ERC-1155 and ERC-20 non-fungible token standard with hardhat framework. After deploying onto the Ethereum blockchain, users will be able to play the game by interacting with the smart contract through DAPP’s front-end interface.

Runner Game :
Just hit any key to start the game.Hit the spacebar to overcome an obstacle in the game.The objective is to survive as long as possible.The game will stop once you fail to avoid the next obstacle.
Users can acquire rewards as game tokens and NFT's depending on their score,once the game is finished.


## ERC - Tokens
### ERC-20 : 
ERC-20 is the technical standard for fungible tokens created using the Ethereum blockchain. A fungible token is one that is interchangeable with another token—where the well-known non-fungible tokens (NFTs) are not interchangeable.

### ERC-1155 : 
ERC1155 is a novel token standard that aims to take the best from previous standards to create a fungibility-agnostic and gas-efficient token contract. ERC1155 draws ideas from all of ERC20, ERC721, and ERC777.


## Contracts
You can find contract detail under `contracts/` directory:
- [`RunTokens.sol`](./contracts/RunTokens.sol):
    The implementation of game execution.

- [`RunnerCollection.sol`](./contracts/CryptoHerosToken.sol):
    The implementation of NFT.

## Technical stack

### Frontend
- HTML
- CSS
- JS
- Bootstrap

### Smart contract/Solidity
- Hardhat

## Requirements

* NodeJS 8.0+ recommended.
* Windows, Linux or Mac OS X.

## How To Install Dependencies

### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
$ cd contracts
```
```
$ npm install
```

### 3. Deploy NFT collection to Polygon Mumbai testnet
- Setup your env file with both private key and mumbai RPC 
```
$ $ npx hardhat run scripts/deployNFTCollection.js --network mumbai
```

### 4. Deploy Run token to Polygon Mumbai testnet
- Setup your env file with both private key and mumbai RPC 
```
$ $ npx hardhat run scripts/deployRunToken.js --network mumbai
```

### 5. Provide the smart contract addresses in blockchain.js file

Images in the game are taken from https://www.flaticon.com/

## Playground

We already deployed contracts to [Polygonscan](https://mumbai.polygonscan.com/) network. You can play with them RIGHT NOW.

| Contract         | Token address | Transaction hash
|------------------|---------------|---------------------
| RunToken         | [0x2205c15313a4dc0ECcdF48415339e85c4d254998](https://mumbai.polygonscan.com/address/0x2205c15313a4dc0ECcdF48415339e85c4d254998) | [0x50e82eb3653412740cad6f41c34a8b5e23b8f20b9f9fb44a86e4f5f124d52d7b](https://mumbai.polygonscan.com/tx/0x50e82eb3653412740cad6f41c34a8b5e23b8f20b9f9fb44a86e4f5f124d52d7b)
| RunnerCollection | [0x6584E1aE71c71B30CC77751A2aAc2788297c39dB](https://mumbai.polygonscan.com/address/0x6584E1aE71c71B30CC77751A2aAc2788297c39dB) | [0x181372dba66a70ff1bd6016ebd7a6057178ffad781f7f10f081755130a39d755](https://mumbai.polygonscan.com/tx/0x181372dba66a70ff1bd6016ebd7a6057178ffad781f7f10f081755130a39d755)





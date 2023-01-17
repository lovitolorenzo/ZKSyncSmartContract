# ZKSync-SmartContract

This project is a practical example of how to use the ZKSync library, Solidity, Node.js with TypeScript for the back-end, Hardhat as web3 framework, and Ethers.js to interact with a smart contract deployed on the ZKSync testnet.

## Getting Started

Clone the repository: git clone https://github.com/[YOUR_USERNAME]/ZKSync-SmartContract.git

Install the dependencies: yarn

Start the project: yarn start

## Project Structure

The project contains the following files and directories:

contracts: contains the Solidity smart contract Greeter.sol
deploy: contains the back-end code written in Node.js with TypeScript
package.json: contains the project dependencies and scripts
hardhat.config.ts: contains the configuration for Hardhat, the web3 framework used to interact with the contract and the ZKSync testnet.

## Interacting with the Smart Contract

The Greeter.sol smart contract is deployed on the ZKSync testnet and allows for the following actions:

Setting a greeting message
Retrieving the current greeting message
The contract is interfaced with using the ethers.js library, and the Hardhat framework is used to interact with the contract and the ZKSync testnet.

## Dependencies

This project uses the following dependencies:

@matterlabs/hardhat-zksync-deploy: A Hardhat extension that allows the deployment of smart contracts on the ZKSync network.
@matterlabs/hardhat-zksync-solc: A Hardhat extension that allows the compilation of smart contracts using the ZKSync-compatible version of the Solidity compiler.
ethers: A library for interacting with Ethereum-compatible networks
hardhat: A development environment for building and testing smart contracts
ts-node: A TypeScript execution and REPL for node.js
typescript: A superset of JavaScript that adds types
zksync-web3: A library for interacting with the ZKSync network
dotenv: A zero-dependency module that loads environment variables from a .env file
Conclusion
This project serves as a practical example of how to use the ZKSync library and Solidity to interact with a smart contract on the ZKSync testnet. Feel free to use this project as a starting point for your own projects and remember that you can always join the development community of ZKSync for more help.

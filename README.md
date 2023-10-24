# Ethereum Smart Contract Assessment

This project for metacrafters passed by Jewel contains a simple Ethereum smart contract written in Solidity. The contract allows for depositing and withdrawing funds, as well as burning a specified amount of funds.

## Features

- **Deposit**: Users can deposit ETH into the contract.
- **Withdraw**: Users can withdraw ETH from the contract.
- **Burn**: Owner can burn a specified amount of ETH from the contract.

## Getting Started

### Prerequisites

- Node.js and npm (Node Package Manager) installed on your machine.
- An Ethereum wallet with access to a test network (e.g., Ropsten, Rinkeby) or a local blockchain setup (e.g., Ganache).

### Installing Dependencies

- First terminal type: npm i
- second terminal type: npx hardhat node
- third terminal, type: npx hardhat run --network localhost scripts/deploy.js
- Back in the first terminal, type npm run dev to launch the front-end.
- After this, the project will be running on your localhost. Typically at http://localhost:3000/

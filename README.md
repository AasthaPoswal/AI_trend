# Trend Prediction

## Description
Trend Prediction is a predictive analytics smart contract that leverages AI-generated data to forecast outcomes and store results on-chain. This Solidity-based contract enables secure and transparent trend predictions, allowing users to retrieve AI-driven insights directly from the blockchain.

## Features
- Store AI-generated trend predictions
- Categorize predictions based on trend type
- Secure and immutable storage on the Ethereum blockchain
- Retrieve stored predictions with ease

## Smart Contract Details
- **Language:** Solidity
- **Compiler Version:** 0.8.0
- **Access Control:** Only the contract owner can add predictions
- **Storage:** Mapping structure to maintain trend records

## Functions
- `addTrend(string memory _category, string memory _prediction)`: Adds a new AI-based trend prediction (owner only).
- `getTrend(uint256 _trendId)`: Retrieves a stored trend prediction by ID.

## Deployment
1. Install Solidity compiler.
2. Deploy the contract on an Ethereum-compatible blockchain.
3. Interact with the contract using Web3.js, Hardhat, or Remix IDE.

## Usage
- AI-driven trend analysis for various industries.
- On-chain storage for predictive analytics.
- Transparent and decentralized forecasting system.

## Author
Developed by Aastha


## Smart Contract Address : 
0x2218b3f355eA0d2e29ba28ee7b079BB60Fe06A29

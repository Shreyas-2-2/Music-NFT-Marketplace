MELO: NFT Music Player

Introduction

MELO is a cutting-edge NFT Music Player that empowers artists to create and distribute their music as unique digital assets on the blockchain. Fans can collect, play, and experience music in a revolutionary way.

Technology Stack & Tools

Smart Contract Development: Solidity
Frontend Development: JavaScript (React)
Blockchain Interaction: Ethers.js
Development Framework: Hardhat
Metadata Storage: IPFS
Routing: React Router

Requirements

Node.js: Version below 16.5.0 is recommended for compatibility. You can download it from the official website: https://nodejs.org/en

Getting Started

Clone/Download the Repository:
Use Git to clone the repository locally

Install Dependencies:
Navigate to the project directory and install all necessary dependencies:

Bash
cd music-nfts
npm install

Start Development Blockchain:

Run a local development blockchain using Hardhat:

Bash
npx hardhat node

This starts a local Ethereum node that simulates a real blockchain for development purposes.

Connect MetaMask:

Locate the private key(s) for the development blockchain accounts provided in Hardhat.
Import these private keys into your MetaMask wallet.
Connect MetaMask to the Hardhat blockchain network running at http://127.0.0.1:8545.
If you haven't added Hardhat to MetaMask:

Open a browser and access MetaMask.
Click the network dropdown (usually shows "Mainnet").
Select "Add Network".
In the provided fields, enter the following details:
Network Name: Hardhat
New RPC URL: http://127.0.0.1:8545
Chain ID: 31337
Click "Save".
Deploy Smart Contracts:
Run the script to migrate your smart contracts to the development blockchain:

Bash
npm run deploy

This deploys the smart contracts defined in Solidity to the local blockchain.

Run Tests:
Ensure your smart contracts function as expected by running unit tests:

Bash
npm test

Launch Frontend:
Start the React development server to run the frontend application:

Bash
npm run start

This will launch MELO in your default web browser, typically at http://localhost:3000/.

Additional Notes

By following these steps, you'll have a fully functional development environment for MELO, the NFT Music Player. Feel free to explore the codebase, customize features, and contribute to the project's growth.

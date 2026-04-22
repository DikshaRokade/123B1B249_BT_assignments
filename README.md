# 123B1B249_BT_assignments
# Blockchain Lab Assignments

**Name:** Diksha Rokade
**PRN:** 123B1B249
**Course:** Blockchain Technology
**Institute:** Pimpri Chinchwad College of Engineering, Pune

-----

## Assignments Overview

|No.|Topic                     |Description                                       |
|---|--------------------------|--------------------------------------------------|
|1  |Smart Contract Development|Write and deploy a Solidity smart contract locally|
|2  |Polygon Deployment        |Deploy contract to Polygon Amoy Testnet           |
|3  |Web Interface + MetaMask  |Build a frontend to interact with the contract    |
|4  |IPFS Integration          |Upload and retrieve files using IPFS / Pinata     |
|5  |DAO Smart Contract        |Build a Decentralized Autonomous Organization     |

-----

## Tech Stack

- Solidity 0.8.20
- Hardhat
- MetaMask
- Ethers.js
- Polygon Amoy Testnet
- IPFS / Pinata

-----

## How to Run

### Setup

```bash
git clone https://github.com/YOUR_USERNAME/blockchain-lab-assignments.git
cd blockchain-lab-assignments
npm install
```

### Assignment 1

```bash
cd assignment-1
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost
```

### Assignment 2

```bash
cd assignment-2
npx hardhat run deploy.js --network amoy
```

### Assignment 3

```bash
cd assignment-3
# Open index.html in browser
```

### Assignment 4

```bash
cd assignment-4
node upload.js
```

### Assignment 5

```bash
cd assignment-5
npx hardhat run scripts/deploy.js --network amoy
```

-----

## Repository Structure

```
blockchain-lab-assignments/
├── README.md
├── hardhat.config.js
├── package.json
├── .env
├── assignment-1/
├── assignment-2/
├── assignment-3/
├── assignment-4/
└── assignment-5/
```

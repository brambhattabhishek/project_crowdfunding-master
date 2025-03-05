# Crowdfunding Platform

This repository contains both the **client** (frontend) and **server** (backend) for a blockchain-based crowdfunding platform.

## Table of Contents
- [Client (Frontend)](#client-frontend)
- [Server (Backend)](#server-backend)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [License](#license)

---

## Client (Frontend)

### 📌 Features
- User-friendly crowdfunding platform UI
- Connects with blockchain wallet (MetaMask)
- Displays active crowdfunding campaigns
- Allows users to create and contribute to campaigns
- Uses Web3.js or Ethers.js to interact with smart contracts

### 🛠 Tech Stack
- **Frontend Framework**: React.js, Next.js
- **State Management**: Redux Toolkit
- **Blockchain Integration**: Ethers.js / Web3.js
- **UI Framework**: Tailwind CSS / Material UI

### 🚀 Getting Started
```sh
cd client
npm install
npm start
```

---

## Server (Backend)

### 📌 Features
- Smart contract interactions (fundraising logic)
- Campaign management API
- User authentication & authorization
- Payment handling with crypto wallets
- Decentralized storage (IPFS / Arweave)

### 🛠 Tech Stack
- **Backend Framework**: Node.js, Express.js
- **Blockchain**: Ethereum / Polygon (Solidity Smart Contracts)
- **Database**: MongoDB / Firebase (optional for user data)
- **Storage**: IPFS / Arweave
- **Authentication**: JWT (JSON Web Tokens)

### 🚀 Getting Started
```sh
cd server
npm install
npm start
```

### 🔗 Smart Contract Deployment (Hardhat)
```sh
cd server/contracts
npx hardhat compile
npx hardhat run scripts/deploy.js --network <network>
```

---

## Technologies Used
| Layer       | Technology |
|------------|------------|
| Frontend   | React.js, Next.js, Tailwind CSS |
| Backend    | Node.js, Express.js |
| Blockchain | Solidity, Hardhat, Ethers.js |
| Storage    | IPFS, Arweave |
| Database   | MongoDB / Firebase |

---

## License
This project is licensed under the MIT License.


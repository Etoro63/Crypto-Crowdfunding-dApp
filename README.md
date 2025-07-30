# 🚀 Crypto-Crowdfunding-dApp

A decentralized crowdfunding platform built on the blockchain. This dApp allows users to create campaigns, contribute cryptocurrency, and track campaign progress in a transparent, trustless manner.



## 📌 Features

- 🏗 Create new crowdfunding campaigns with a goal amount and deadline.
- 💰 Donate cryptocurrency (e.g., ETH or MATIC) to active campaigns.
- 🔎 View campaign details, funding status, and contributor lists.
- 🔐 Connect with MetaMask or other Web3 wallets.
- 📜 Immutable storage of campaigns and contributions on blockchain.
- 🔄 Real-time campaign status updates.

---

## ⚙️ Tech Stack

| Layer        | Technology                         |
|--------------|------------------------------------|
| **Frontend** | React.js, Tailwind CSS, Ethers.js  |
| **Blockchain** | Solidity, Hardhat or Foundry       |
| **Wallet**   | MetaMask, WalletConnect            |
| **Backend (optional)** | IPFS (for images/docs), The Graph (for indexing) |

---

## 🧠 Smart Contract Overview

```solidity
// Example: Pseudo-function
function createCampaign(string memory title, string memory description, uint goal, uint deadline) public {
    // Stores campaign data on-chain
}
```

> The smart contracts handle campaign creation, contributions, and fund withdrawals with built-in logic for success/failure conditions.

---

## 🧪 Installation

### Prerequisites

- Node.js ≥ 16.x
- MetaMask Wallet Extension
- Hardhat or Foundry installed globally

### Clone the Repo

```bash
git clone https://github.com/Etoro63/Crypto-Crowdfunding-dApp.git
cd Crypto-Crowdfunding-dApp
```

### Install Dependencies

```bash
npm install
```

### Compile & Deploy Contracts (Hardhat)

```bash
npx hardhat compile
npx hardhat run scripts/deploy.js --network 

### Run the Frontend

```bash
npm run dev
```

Then visit: [http://localhost:3000](http://localhost:3000)

---

## 📸 Screenshots

> Add UI screenshots here (e.g., homepage, create campaign, donate modal)

---

## ✅ To-Do List

- [ ] Add email notifications via Web3 services
- [ ] Enable token-based campaigns
- [ ] Integrate The Graph for indexing
- [ ] Use IPFS for decentralized media storage

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙋‍♂️ Author

Made with ❤️ by [Etoroabasi](https://github.com/Etoro63)

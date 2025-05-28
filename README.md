# Blockchain-Document-Verification
A decentralized web application for secure document issuance and verification using blockchain technology, ensuring data integrity, tamper-proof validation, and transparent verification of academic, legal, or official documents.
# 🔐 BlockVault - Blockchain-Based Document Verification System

A decentralized web application for secure **document issuance and verification** powered by blockchain technology. Designed for academic, legal, and enterprise-grade document validation.

![Banner](./banner.png) <!-- Replace with your own screenshot or remove -->

---

## 🌟 Features

- ✅ **Document Issuance**: Upload and issue verified documents securely.
- 🔍 **Document Verification**: Verify documents instantly via hash comparison.
- 🔗 **Blockchain-Powered**: Tamper-proof records using Ethereum smart contracts.
- 🔐 **MetaMask Integration**: Authenticate and sign transactions securely.
- 📷 **QR Code Support**: Share documents with QR for easy verification.
- 🌐 **Modern UI**: React.js frontend with a smooth UX and Tailwind CSS.

---

## 🚀 Getting Started

### Prerequisites

- Node.js & npm
- MetaMask wallet
- Hardhat (for local blockchain dev)

---

git clone https://github.com/your-username/blockchain-project.git
cd blockchain-project
npm install

🚀 Running the Project Manually
Step 1: Start the Hardhat Node
bash
cd blockchain
npx hardhat node
Step 2: Deploy the Smart Contract (new terminal)
bash
npx hardhat run ../scripts/deploy.js --network localhost
Step 3: Start the Frontend
bash
cd ../frontend
npm install
npm run dev

# 🗳️ Online Voting System Using Blockchain

A secure, decentralized online voting system built using **Solidity smart contracts**, **Node.js**, and **Truffle framework**. This project aims to bring transparency, immutability, and trust into the digital voting process.

---

## 🔐 Why Blockchain for Voting?

Traditional voting systems face issues like fraud, tampering, and lack of transparency. With blockchain, every vote is:
- 🧾 **Immutable**
- ✅ **Verifiable**
- 🌐 **Transparent**
This ensures election integrity without relying on centralized systems.

---

## 📌 Features

- 🧠 **Smart Contract-Based Voting**: All logic is handled on-chain using Solidity.
- 👤 **Voter Registration**: Admin can register eligible voters.
- 🗳️ **Cast Vote**: Registered users can vote once.
- 📊 **Live Result Tracking**: Real-time vote count (on contract level).
- 🔐 **Tamper-Proof**: Votes can't be changed once cast.
- 📦 **File Structure Organized for DApp Development**

---

## 💻 Tech Stack

| Layer       | Tech Used                     
|------------|-------------------------------
| 💾 Blockchain | Ethereum (Ganache/Testnet)     
| 🧠 Contracts  | Solidity + Truffle             
| 🌐 Backend   | Node.js, Express                
| 🗃️ Database | JSON/local/mock (or can be extended to MongoDB)
| 🧪 Testing   | Mocha/Chai (via Truffle)       
| 🖥️ IDE      | VS Code / Truffle CLI / Ganache 

---

## 📂 Project Structure

├── contracts/ # Solidity smart contracts
├── migrations/ # Deployment scripts for Truffle
├── src/ # Frontend or supporting logic
├── routes/ # Express API routes
├── test/ # Smart contract tests
├── build/ # Compiled contract artifacts
├── database.js # Sample data persistence (can upgrade to DB)
├── truffle-config.js # Truffle configuration
├── package.json # Node.js dependencies

yaml
Copy
Edit

---

## ⚙️ How to Run

### 🚀 Prerequisites
- Node.js & npm
- Truffle (`npm install -g truffle`)
- Ganache (local blockchain)
- MetaMask (optional for frontend interaction)

### 🛠 Setup & Run

```bash
# Install dependencies
npm install

# Compile smart contracts
truffle compile

# Start local blockchain in Ganache

# Migrate contracts
truffle migrate

# Run the backend
node src/index.js
Replace src/index.js with your actual entry point if different.

✅ Security Notes
Only registered voters can vote (based on mapping logic)

Each account can vote only once

Admin-only contract functions are protected with modifiers

🙌 Final Thoughts
Blockchain brings trust and transparency to voting systems. This project is a hands-on implementation for students and developers to understand how decentralized governance can be modeled using Ethereum and smart contracts.


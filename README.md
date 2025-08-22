

📦 Blockchain-based Product Tracking System

An end-to-end supply chain tracking DApp built on Ethereum. This project demonstrates how blockchain can bring transparency, security, and traceability to product movement from manufacturer → distributor → retailer → customer.

⸻

🚀 Features
	•	Product Registration – Register products with SKU, name, and IPFS document hash.
	•	Ownership Transfer – Track changes in product ownership across multiple parties.
	•	Checkpoints Logging – Add checkpoints (location, note) at each stage.
	•	State Management – Update lifecycle states: Created, InTransit, Delivered, Returned, Recalled.
	•	Timeline & History – View complete product history (owners + checkpoints).
	•	Web3 Frontend – React + ethers.js interface for interaction.

⸻

🛠️ Tech Stack
	•	Smart Contract: Solidity (Hardhat framework)
	•	Blockchain: Ethereum / Sepolia Testnet
	•	Frontend: React + Vite + ethers.js
	•	Storage (optional): IPFS for product documents/certificates
	•	Deployment: Hardhat 

⚙️ Setup Instructions

1. Clone Repository

git clone https://github.com/your-username/product-tracker.git
cd product-tracker

2. Install Dependencies

npm install

3. Compile Smart Contract

npx hardhat compile

4. Deploy to Testnet (Sepolia)

Update .env with your wallet and RPC:

RPC_URL=https://sepolia.infura.io/v3/YOUR_PROJECT_ID
PRIVATE_KEY=0xYOUR_PRIVATE_KEY

Then deploy:

npx hardhat run scripts/deploy.js --network sepolia

5. Run Demo Script

CONTRACT_ADDRESS=0xDeployedAddressHere npx hardhat run scripts/demo.js --network sepolia

6. Start Frontend

cd tracker-ui
npm install
npm run dev



✨ Contributors
	•	Abrar Ahamed (220071601012)
	•	Akmal mohamed (220071601025)

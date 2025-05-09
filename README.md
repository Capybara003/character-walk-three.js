# 🎮 Character Walk Three.js – Web3-Enabled 3D Game

Character Walk Three.js is an immersive 3D browser-based game that integrates blockchain technology using smart contracts. Built with **Three.js** for rendering and **Solidity** for blockchain interactions, this project offers a seamless blend of interactive gameplay and decentralized features.

## 🌐 Live Demo

Experience the game: [https://character-walk-threejs.vercel.app/](https://character-walk-threejs.vercel.app/)

## 🚀 Features

- **3D Character Movement**: Navigate a 3D environment with smooth character animations.
- **Smart Contract Integration**: Interact with Ethereum smart contracts for in-game transactions and asset management.
- **Web3 Wallet Connectivity**: Connect your Web3 wallet (e.g., MetaMask) to engage with blockchain features.
- **Responsive Design**: Optimized for various devices and screen sizes.

## 🛠️ Technologies Used

- **Frontend**: Three.js, JavaScript, HTML, CSS
- **Blockchain**: Solidity, Ethereum, Web3.js
- **Deployment**: Vercel

## 🧰 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- A Web3 wallet (e.g., MetaMask)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/character-walk-threejs.git
   cd character-walk-threejs
  ```
2. **Install dependencies:**
  ```bash
  npm install
  # or
  yarn install
  ```
3. **Configure Environment Variables:**

Create a .env.local file in the root directory and add the following variables:
  ```
  NEXT_PUBLIC_CONTRACT_ADDRESS=your_smart_contract_address
  NEXT_PUBLIC_INFURA_ID=your_infura_project_id
  ```
4. **Run the development server:**
   ```bash
  npm run dev
   # or
   yarn dev
  ```
5. **Access the application:**

Open http://localhost:3000 in your browser.
## ⚙️ Configuration
Smart Contract Deployment
Deploy your Solidity smart contract to the Ethereum network using tools like Remix or Hardhat. Ensure the contract address is correctly set in the .env.local file.

### Web3 Integration
The application uses Web3.js to interact with the Ethereum blockchain. Ensure your wallet is connected and configured to the correct network.

## 📄 License
This project is licensed under the MIT License.

## 🤝 Acknowledgements
- Three.js for the 3D rendering library.

- Ethereum for the blockchain platform.

- Web3.js for blockchain interactions.

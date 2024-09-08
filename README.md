# Blockchain-Infused NFT Concentration Game

## Overview

The "Blockchain-Infused NFT Concentration Game" project integrates classic card game mechanics with modern Web 3 technologies, including blockchain, decentralized storage, and smart contracts. This project reimagines the traditional Concentration card game by leveraging the power of Web 3 to offer enhanced security, true ownership of in-game assets, and a decentralized gaming ecosystem.

## Key Features

- **Web 3 Integration**: Seamless incorporation of blockchain technology, decentralized storage, and smart contracts.
- **Enhanced Security**: Improved transparency and security through blockchain technology.
- **True Ownership**: Players have true ownership of in-game assets via NFTs.
- **Cross-Platform Play**: Enjoyable on various devices and platforms with consistent progress.
- **Community Engagement**: A decentralized ecosystem for collaboration, trading, and competition.
- **Educational Value**: Introduction to blockchain technology in a fun and interactive manner.

## Technologies Used

- **Web3.js**: Facilitates interaction with the Ethereum blockchain and frontend integration.
- **ERC721**: Standard for implementing non-fungible tokens (NFTs) to ensure compatibility.
- **Truffle**: Development framework for Ethereum smart contracts and DApps.
- **Ganache**: Local blockchain network for development and testing.
- **Solidity**: Programming language for writing smart contracts.

## File Structure

- **`public/`**: Contains public assets like images and HTML files.
  - `index.html`: Main HTML file.
  - `favicon.ico`: Favicon for the application.
  - `manifest.json`: Web app manifest file.

- **`src/`**: Source code directory.
  - **`components/`**: React components for the frontend.
    - `App.js`: Main application component.
    - `App.css`: Styles for the application.
  - **`index.js`**: Entry point for the React application.
  - **`serviceWorker.js`**: Service worker for offline functionality.

- **`blockchain_game/src/abis/`**: Contains ABI (Application Binary Interface) JSON files for smart contracts.
  - `MemoryToken.json`: ABI for the MemoryToken smart contract.

- **`contracts/`**: Solidity smart contracts.
  - `ERC721Full.sol`: Implementation of ERC721 full contract.
  - `MemoryToken.sol`: Smart contract for the MemoryToken.
  - `Migrations.sol`: Migrations contract for Truffle.

- **`test/`**: Contains test files for smart contracts.
  - `MemoryToken.test.js`: Test suite for the MemoryToken smart contract.

- **`migrations/`**: Truffle migrations scripts for deploying contracts.
  - `1_initial_migration.js`: Initial migration script.
  - `2_deploy_contracts.js`: Deployment script for smart contracts.

- **`.babelrc`**: Babel configuration file.
- **`.gitignore`**: Git ignore file for excluding unnecessary files.
- **`package.json`**: Project metadata and dependencies.
- **`package-lock.json`**: Locked versions of dependencies.
- **`truffle-config.js`**: Configuration file for Truffle.

## Getting Started

1. **Clone the Repository**
   
2. **Install Dependencies**
   npm install

3. **Start the Local Blockchain**
   npx ganache-cli

4. **Deploy Smart Contracts**
   npx truffle migrate

5. **Run the Application**
   npm start

6. **Run Tests**
   npx truffle test

## Contributing

Feel free to open issues or submit pull requests if you have suggestions or improvements. Your contributions are welcome!

# Blockchain-Infused NFT Concentration Game

## Overview

The "Blockchain-Infused NFT Concentration Game" project integrates classic card game mechanics with modern Web 3 technologies, including blockchain, decentralized storage, and smart contracts. This project reimagines the traditional Concentration card game by leveraging the power of Web 3 to offer enhanced security, true ownership of in-game assets, and a decentralized gaming ecosystem.

## Working of the Project

The "Web 3 Based Concentration Card Game" project demonstrates a fusion of traditional card gaming with modern blockchain technology, specifically leveraging Web 3 concepts to create a unique and immersive experience. At the heart of this project is the deployment of smart contracts, particularly the `MemoryToken.sol` contract, which governs the NFT-based card system. This smart contract ensures that each card in the Concentration game is represented as a non-fungible token (NFT), thereby guaranteeing its uniqueness and ownership. The use of Truffle and Ganache facilitates the development, testing, and deployment of these smart contracts on a local blockchain network before going live on Ethereum. The frontend of the game is developed using React and interacts with the blockchain through Web3.js, enabling players to manage their NFTs and participate in the game securely. The game incorporates the classic Concentration rules, with card matching and scoring handled through the smart contracts, ensuring a fair and transparent gameplay experience. Additionally, the decentralized nature of the project allows for cross-platform access, meaning players can enjoy the game on various devices without losing progress, thanks to the decentralized infrastructure. This setup fosters a robust gaming ecosystem where players can trade, compete, and collaborate within a community, free from intermediaries. The project not only enhances the gaming experience but also serves as a practical demonstration of Web 3 technologies, showcasing how blockchain can revolutionize traditional gaming concepts.

## Use of the Project

To engage with the "Web 3 Based Concentration Card Game," users start by accessing the web application and connecting their Ethereum wallet. This integration allows players to manage their NFT cards and participate in gameplay. The game follows the traditional Concentration rules, where players aim to match pairs of cards, but with the added dimension of NFT ownership. Players interact with the game through a user-friendly interface, where they can view, trade, and manage their NFT cards. Each card is a unique ERC721 token, ensuring true ownership and the ability to trade or sell within the game's ecosystem. The decentralized nature of the game provides a transparent and fair experience, as all game actions are recorded on the blockchain. For contributors, the project is open for enhancements and improvements. Community members can contribute by addressing issues, proposing new features, or submitting code changes via GitHub. The project also serves an educational purpose, offering insights into blockchain technology and its applications in gaming. It provides a hands-on example of how smart contracts, decentralized storage, and NFTs can be integrated into a traditional game, making it an informative resource for those interested in the intersection of blockchain and gaming.

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

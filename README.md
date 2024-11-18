# GetMood-dApp

A decentralized application (dApp) built on Ethereum that allows users to **set** and **get** their mood on the blockchain. This project is powered by **Solidity**, **Ethers.js**, and the **Sepolia testnet**.

---

## 🚀 Features

- **Set Mood**: Input your current mood and store it on the blockchain.
- **Get Mood**: Retrieve your previously stored mood from the blockchain.
- **Decentralized**: Powered by Ethereum smart contracts, ensuring security and immutability.
- **Simple UI**: Intuitive and clean user interface for seamless interaction.
- **Wallet Integration**: Easily connect your wallet through MetaMask.

---

## 📜 Project Overview

This project demonstrates the basics of creating a decentralized application (dApp) by integrating the Ethereum blockchain with a simple web-based interface. Users can set and retrieve their moods, which are stored securely on the blockchain via a smart contract.

**Smart Contract**:  
The core of the application is a Solidity smart contract named `MoodDiary`. It features two functions:  
- `setMood`: Accepts a mood string and stores it on the blockchain.  
- `getMood`: Retrieves the mood string from the blockchain.

**Front-End**:  
The front-end, built with HTML, CSS, and JavaScript, interacts with the smart contract using **Ethers.js**.

**Blockchain Network**:  
The project uses the **Sepolia Testnet** for testing and deployment. 

---

## 🛠️ Tech Stack

### Smart Contract
- **Solidity**: For writing the `MoodDiary` smart contract.
- **Ethereum**: Blockchain platform for deploying the smart contract.
- **Remix IDE**: Used for writing and deploying the smart contract.

### Front-End
- **HTML/CSS**: For creating the user interface.
- **JavaScript**: To handle interactions with the blockchain using Ethers.js.
- **Ethers.js**: A library for blockchain interactions.

### Tools and Dependencies
- **MetaMask**: Wallet for interacting with the dApp.
- **Sepolia Testnet**: Ethereum test network for development and testing.

---

## 📂 Project Structure
   ```plaintext
   ├── index.html       # Front-end of the dApp
   ├── scripts.js       # JavaScript logic to interact with the smart contract
   ├── style.css        # CSS for styling the dApp
   └── mood.sol         # Smart contract written in Solidity
   ```
---
## 💻 How to Run the Project Locally

1. Clone this repository
   ```bash
   git clone https://github.com/Ayushpremrocks/GetMood-dApp
   cd mood-diary
   ```
2. Deploy the smart contract:
  - Use Remix IDE to deploy the mood.sol contract on the Sepolia Testnet.
  - Copy the deployed contract's address and replace the value of MoodContractAddress in scripts.js.
3. Serve the front-end:
  - Open index.html in a browser (e.g., via Live Server in VS Code).
4. Connect MetaMask:
  - Ensure MetaMask is configured for the Sepolia Testnet.
  - Connect your wallet to the dApp.
5. Interact with the dApp:
  - Input a mood and click Set Mood to store it on the blockchain.
  - Click Get Mood to retrieve your current mood.
---
🙌 Acknowledgments
  - Ethereum Community for providing resources and documentation.
  - MetaMask for seamless wallet integration.
  - Ethers.js for simplifying interactions with Ethereum.
---
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


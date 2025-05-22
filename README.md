# 🗳️ Decentralized Voting System Using NFTs

A revolutionary approach to secure, transparent, and tamper-proof elections leveraging blockchain technology and Non-Fungible Tokens (NFTs). This decentralized voting system ensures that only verified participants can vote, and every vote is recorded immutably on-chain, guaranteeing integrity without reliance on centralized authorities.

## 🚀 About the Project

This **Decentralized Voting DApp** introduces a **voter eligibility mechanism through NFTs**. Each eligible voter is issued a unique NFT representing their right to vote. Votes are cast via smart contracts on the Ethereum blockchain, ensuring transparency, anonymity, and immutability.

No central authority can alter the vote count, and NFT ownership guarantees one vote per verified wallet, preventing double voting and fraudulent participation.

## 🎯 Key Features

* 🛡️ **NFT-Based Voter Identity** — Each voter receives an NFT that grants voting rights.
* 📜 **Smart Contract Powered Voting** — Every vote is a transaction recorded on the blockchain.
* 🔍 **Transparent & Auditable** — Real-time vote counts visible to everyone.
* 🔒 **Immutable and Fraud-Resistant** — No third-party control, no tampering possible.
* 🌍 **Decentralized Participation** — Anyone with a valid NFT and wallet can vote from anywhere.

## ⚙️ Tech Stack

* **Blockchain Platform:** Ethereum
* **Smart Contract Language:** Solidity
* **NFT Standard:** ERC-721
* **IDE for Smart Contract Deployment:** [Remix IDE](https://remix.ethereum.org/)
* **Web3 Provider:** MetaMask (and compatible wallets)
* **Faucets:** For acquiring test ETH for deployment and voting transactions

## 📦 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/PrazwalR/Decentralized-Voting-Dapp.git
   cd Decentralized-Voting-Dapp
   ```

2. Install a Web3 wallet such as [MetaMask](https://metamask.io/).

3. Connect to a supported Ethereum testnet (e.g., Sepolia, Goerli).

4. Acquire free test ETH from a faucet for deploying contracts and voting.

5. Open [Remix IDE](https://remix.ethereum.org/), load the smart contracts, compile, and deploy them using your connected wallet.

6. Use the generated ABI and contract address to interact with the contracts through a DApp frontend or Web3 tools.

## 💸 Getting Test ETH

Use any of the following testnet faucets:

* [Sepolia Faucet](https://sepoliafaucet.com/)
* [Goerli Faucet](https://goerlifaucet.com/)
* [Alchemy Faucet](https://faucet.alchemy.com/)

Transfer test ETH to your wallet address for contract deployment and voting.

## 🎨 How It Works

1. **NFT Minting:**

   * Admin mints an ERC-721 NFT for each eligible voter.
   * The NFT represents the right to cast a single vote.

2. **Voting Process:**

   * Eligible voters connect their wallet.
   * The smart contract checks for NFT ownership.
   * Voters submit their vote transaction.
   * The contract records the vote immutably and prevents multiple votes from the same NFT holder.

3. **Vote Counting:**

   * Votes are tallied in real-time on-chain.
   * Final results are publicly verifiable and immutable.

## 🧑‍💻 Contributing

Contributions are encouraged! To improve this project:

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to your branch: `git push origin feature/YourFeature`
5. Open a pull request.

## 📌 Roadmap & Future Enhancements

* NFT metadata customization for voter identity verification.
* Anonymous voting mechanism via Zero-Knowledge Proofs.
* React & Ethers.js-based frontend integration.
* DAO-based proposal and voting management for decentralized governance.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Project Repository

Check out the complete project here:

👉 [Decentralized Voting DApp](https://github.com/PrazwalR/Decentralized-Voting-Dapp)

# KaseiCoin: The Martian Cryptocurrency

## 🚀 Introduction

In the vast expanse of the universe, as humanity takes its first steps on the red planet, a new era of financial systems emerges. Welcome to the Martian frontier, where KaseiCoin reigns supreme!

## 🌌 Background

The Martian Aerospace Agency, after rigorous years of testing and selection, has chosen you from the best of Earth's fintech professionals. Your mission, should you choose to accept it, is to architect the financial backbone of the first human colony on Mars. Drawing inspiration from Earth's blockchain technology, you embark on creating KaseiCoin, the official cryptocurrency of Mars. (Fun Fact: "Kasei" translates to "Mars" in Japanese!)

## 🪐 KaseiCoin Specifications

- **Type**: Fungible Token
- **Standard**: ERC-20 compliant
- **Purpose**: To facilitate transactions within the Martian colony and allow Earthlings to convert their terrestrial currency before their Martian journey.

## 🌠 What's in the Box?

1. **KaseiCoin Token**: An ERC-20 compliant fungible token, minted through a crowdsale contract.
2. **Crowdsale Contract**: Manages the entire crowdsale process, allowing users to exchange ether for KAI (KaseiCoin tokens).
3. **Visual Evidence**: A comprehensive guide, either through a captivating video or detailed screenshots, showcasing each phase of the challenge.

## 📂 Files

- [Starter Code](#)

## 🛠 Instructions

### 1. Crafting the KaseiCoin Token Contract

- Import the KaseiCoin.sol starter file into Remix IDE.
- Integrate contracts from the OpenZeppelin library: ERC20, ERC20Detailed, and ERC20Mintable.
- Construct the KaseiCoin contract, inheriting the above OpenZeppelin contracts.
- Compile using the 0.5.5 compiler version.
- Document your progress with screenshots for evidence.

### 2. Building the KaseiCoin Crowdsale Contract

- Start with the KaseiCoinCrowdsale.sol starter code.
- Inherit OpenZeppelin's Crowdsale and MintedCrowdsale contracts.
- Define the crowdsale parameters: rate, wallet, and token.
- Again, compile using the 0.5.5 compiler version and capture screenshots.

### 3. Assembling the KaseiCoin Deployer Contract

- Work with the KaseiCoinCrowdsaleDeployer contract in the KaseiCoinCrowdsale.sol starter code.
- Store addresses for the KaseiCoin and KaseiCoinCrowdsale contracts.
- Construct the KaseiCoinCrowdsaleDeployer with parameters: name, symbol, and wallet.
- Compile, check, debug, and screenshot!

### 4. Launching the Crowdsale on a Local Blockchain

- Deploy using Remix, MetaMask, and Ganache.
- Test the crowdsale's functionality.
- Record your steps either through a video or screenshots.

### 5. (Optional) Enhance the Crowdsale Contract with OpenZeppelin

- Extend your contract using OpenZeppelin's CappedCrowdsale, TimedCrowdsale, and RefundablePostDeliveryCrowdsale.
- Import the necessary OpenZeppelin contracts.
- Update the KaseiCoinCrowdsale and KaseiCoinCrowdsaleDeployer contracts.
- Compile, test, and document.

## 🌟 Conclusion

As the Martian horizon beckons, KaseiCoin stands as a testament to human ingenuity and adaptability. This README serves as your guide in this interstellar financial journey. Safe travels, and may your KaseiCoins always shine bright!

---

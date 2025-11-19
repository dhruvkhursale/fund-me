# Fund Me – Decentralized Crowdfunding Smart Contract

A decentralized crowdfunding application built using **Solidity**, **Hardhat**, and **Chainlink Price Feeds**.  
Users can fund the contract using **ETH**, and the owner can withdraw the collected funds securely.

## Features
- Accept ETH donations from users  
- Minimum funding requirement in **USD**  
- Tracks every funder  
- Owner-only withdrawal  
- Gas-optimized  
- Uses fallback and receive functions  

## Tech Stack
| Component | Technology |
|----------|------------|
| Smart Contract | Solidity 0.8+ |
| Blockchain Framework | Hardhat |
| Oracle | Chainlink Price Feed |
| Testing | Hardhat + Ethers.js |

## Project Structure
```
fundme/
 ├── contracts/
 │     ├── FundMe.sol
 │     └── PriceConverter.sol
 ├── scripts/
 │     └── deploy.js
 ├── test/
 ├── hardhat.config.js
 └── README.md
```

## Installation
```
git clone https://github.com/yourusername/fundme.git
cd fundme
npm install
```

## Deployment (Hardhat)
```
npx hardhat run scripts/deploy.js
```

## Testing
```
npx hardhat test
```

## Author
Aditya Waghamare  
Smart Contract Developer

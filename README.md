# dOptions

*Your Gateway to Truly Decentralized Options Trading*

- **[Video Demo](https://youtu.be/OV_RVZxUJ38)**
- **[Automation Demo](https://youtu.be/AZyX4mt8d8c)**
- **[Code Walkthrough](https://youtu.be/anJyjkQ6W0g)**
- **[Live Website](https://doptions.vercel.app/)**
- **[Pitchdeck](https://doptions-uokcwbj.gamma.site/)**

## Overview
dOptions is a decentralized options protocol allowing users to create and trade options contracts with full customizability. It supports both CALL and PUT Options, offering unique features like Basket Options.

## Problem
Traditional financial markets have seen a significant increase in the volume of options traded, often surpassing the volume of equities. However, the current on-chain options protocols lack true decentralization and flexibility. Most existing solutions do not allow individual users to write their own options, and none offer the level of customizability that traders seek. This gap hinders the adoption and innovation of decentralized finance (DeFi) solutions in the options trading market.

## Solution
dOptions provides a comprehensive solution by enabling users to create and trade options on their own terms, thus ensuring true decentralization and customizability. Our protocol supports the creation and trading of both CALL and PUT Options along with Basket Options, allowing users to define their own strike prices, premiums, expiration dates, and quantities. This flexibility empowers users to tailor options contracts to their specific needs and trading strategies.

Additionally, dOptions plans to introduce advanced options types such as Rainbow Options and Barrier Options, further enhancing the trading experience. Our integration with Chainlink Price Feeds ensures reliable and accurate price data, both on-chain and off-chain. This integration guarantees that all transactions are based on trustworthy and tamper-proof price information.

To cater to the growing demand for automated trading strategies, dOptions includes support for AI-driven automation clients. These clients enable users to implement and execute automated trading strategies, optimizing their trading activities and maximizing their returns. Our current basic automation client is available for users to try, with more advanced versions planned for future releases.

### Project Highlights
- **Fully Customizable Options**: Users can create CALL and PUT options with custom parameters.
- **Advanced Option Types**: Supports advanced options like Basket Options.
- **Automated Strategies**: Basic AI agent for automated trading strategies.
- **Cross-Chain Support**: Deployable on multiple EVM and non-EVM chains.

### Chainlink Integration
- **Price Feeds**: Utilizes Chainlink Price Feeds for accurate and reliable on-chain and off-chain price data.

## Team
We are experienced web3 developers with a history of building DeFi primitives across various chains. Our team, PsyCode Labs, is dedicated to creating next-gen, multi-chain products. Our lead developer holds a certificate in Decentralized Finance from Coursera.

## Roadmap
### July-August
- Enhance UI/UX
- Implement Basket Options & Secondary Marketplace frontend
- Support for EVM chains like Linea, Canto

### September-October
- Expand option types
- Support for non-EVM chains like Starknet, ICP, Solana
- Fundraising for marketing & incentives

### November
- Soft launch
- Develop AMM-based secondary marketplace (V2)
- TBD

## Tech Stack
- **Foundry**: For smart contract development and testing.
- **NextJS**: For frontend development.
- **Python**: For the automation client using web3.py.

## Installation Guide
### app (Next.js Project)
1. Navigate to the `app` directory.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`

### automation (Python Client)
No installation needed. Ensure `web3.py` is installed if modifications are required.

### contracts (Foundry Project)
1. Navigate to the `contracts` directory.
2. Install Foundry: Follow [Foundry installation guide](https://book.getfoundry.sh/getting-started/installation.html)
3. Build contracts: `forge build`
4. Run tests: `forge test`

## Target Tracks
### Financial Services
Expand the realm of on-chain finance by building new DeFi primitives or solutions that bridge DeFi with TradFi. Utilize Chainlink's offerings to enhance the tokenized asset economy.

### Best MVP of Polygon Cardona
Develop groundbreaking projects leveraging Cardona zkEVM Testnet technology. Show potential for incubation at Polygon Village and demonstrate market potential, user engagement, and team vision.

### Best DeFi dApp of Polygon Amoy
Innovate within the DeFi space on the Polygon PoS network. Projects should demonstrate scalability, user experience, and team expertise.

### Chainlink Price Feeds on zkSync
Deploy projects on zkSync Sepolia Testnet using Chainlink’s Price Feeds. Include thorough documentation and aim to solve tangible problems or build relevant use cases.

### Scroll
Build the latest in web3 on Ethereum and deploy on Scroll Sepolia. Projects should demonstrate tangible problem-solving, community value, and innovative use of Scroll’s capabilities.

## Contract Addresses
### Scroll Sepolia
- **Factory**: 0x6fA6089c99D07769c30dD0966315ea7C80ECe6FD

### Polygon Amoy (PoS)
- **Factory**: 0x4633BFBb343F131deF95ac1fd518Ed4495092063

### Polygon Cardona (zkEVM)
- **Factory**: 0x19Ed533D9f274DC0d1b59FB9C0d5D1C27cba8bb1

### zkSync Sepolia
- **Factory**: 0x1E89E5ccFcd37e244d02B656085844E399B1967C

---

Explore the future of decentralized options trading with dOptions!

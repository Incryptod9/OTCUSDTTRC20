# OTC USDT TRC-20 Institutional Gateway

An exclusive, high-security Over-The-Counter (OTC) asset clearing and collateral management platform engineered specifically for high-volume **USDT (TRC-20)** transactions on the TRON Network. 

This repository contains the institutional-grade Multi-Signature Escrow Smart Contract (`.sol`) and the premium, dark-luxury frontend portal interface designed for seamless enterprise-level operations.

## 🌟 Key Features

*   **Multi-Signature Consensus (2-of-3):** Eliminates single points of failure by requiring explicit transaction approval from at least two authorized parties (Provider, Client, and independent Escrow Agent).
*   **Tailored for TRC-20 (TRON):** Native compatibility with the TRON Virtual Machine (TVM) and the official TR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t USDT smart contract.
*   **Whitelisted Collateral Workflow:** Hardcoded security parameters to ensure funds are exclusively released to the verified recipient's vault.
*   **Premium Dark UI:** An executive dashboard designed with modern Tailwind CSS, featuring automated state trackers for multi-sig consensus visualization.

## 🏗️ Architecture & Stack

*   **Smart Contract:** Solidity `^0.5.15` (Optimized for TRON mainnet deployment via TronScan / TronBox).
*   **Frontend Interface:** Semantic HTML5, Tailwind CSS, and FontAwesome Integration.
*   **Web3 Integration Ready:** Prepared structures for `TronWeb` API bindings.

## 🚀 Quick Deployment Note

1. Compile the `PremiumOtcEscrow.sol` file using Solidity Compiler `0.5.15`.
2. Deploy the contract by passing the verified **Client Address**, **Escrow Agent Address**, and the official **TRON USDT Contract Address** into the constructor.
3. Host the `index.html` via GitHub Pages mapping to your institutional domain (`usdttrc20otc.pp.ua`).

---
*Disclaimer: This repository is intended for institutional testing and collateral staging. Always run complete end-to-end audits on the Shasta Testnet before interacting with real enterprise-grade liquidity on the Mainnet.*

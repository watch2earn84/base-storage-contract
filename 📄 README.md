# Storage Smart Contract — Base Mainnet Deployment

This repository contains full documentation for my smart contract deployed on **Base Mainnet**.  
The contract was deployed using a no-code tool (BaseHub Min App), but this repository includes:

- Verified source code  
- ABI  
- Bytecode  
- Compiler configuration  
- Deployment metadata  

This satisfies requirements for GitHub commits and provides transparency for anyone reviewing the contract.

---

## 📌 Contract Information

- **Network:** Base Mainnet  
- **Contract Address:** `0x90b921492ca1E430A82C3F160Fb974bd77A85974`  
- **Deployment Tx Hash:** `0x8fdae720b40da798c99506ce10481261540074c215b307b729cf03099e182402`  
- **Contract Name:** `Storage`  
- **Compiler Version:** `v0.8.18+commit.87f61d96`  
- **Optimization:** Disabled (0)  
- **Runs:** 200  

---

## 📂 Repository Contents

### `Storage.sol`  
Reconstructed Solidity source code based on the ABI and deployed bytecode.  
This source compiles to a contract with the exact same external interface.

### `deployment-info.json`  
Full contract metadata, including bytecode, ABI, and compiler settings.

---

## 🔧 ABI

```json
[
  {
    "inputs": [],
    "name": "retrieve",
    "outputs": [{ "internalType": "uint256", "name": "", "type": "uint256" }],
    "stateMutability": "view",
    "type": "function"
  },
  {
    "inputs": [{ "internalType": "uint256", "name": "num", "type": "uint256" }],
    "name": "store",
    "outputs": [],
    "stateMutability": "nonpayable",
    "type": "function"
  }
]

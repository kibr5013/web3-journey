# Web3 Journey - Day 1

Exploring Web3 and building projects on the Base blockchain ecosystem. This repo includes smart contracts, deployments, and learning notes.

⚙️ Tech Stack
-Solidity (Smart Contracts)
-Ethereum Virtual Machine (EVM)
-Base Blockchain
-MetaMask Wallet
-Remix IDE
-Git & GitHub

🚀 What I Am Doing
-Writing and deploying smart contracts
-Learning how Base blockchain works
-Connecting wallet with dApps
-Testing transactions on Base network


📦 Smart Contract Example


// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract MyToken {
    string public name = "MyToken";
    string public symbol = "MTK";
    uint8 public decimals = 18;
    uint public totalSupply = 1000000 * 10 ** 18;

    mapping(address => uint) public balanceOf;

    constructor() {
        balanceOf[msg.sender] = totalSupply;
    }
}

--------------------------------------------------------

🔗 Base Network Details
-Network: Base Mainnet

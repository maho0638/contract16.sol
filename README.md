# contract16.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Simple Web3 ownership contract
contract Contract16 {
    address public owner;

    constructor() {
        owner = msg.sender;
    }
}

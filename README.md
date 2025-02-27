# TOKEN-CREATION-ERC-20

"COMPANY": COTECH IT SOLUTIONS

"NAME": MADIHA NAAZ

"INTERN ID": CT08IYC

"DOMAIN": BLOCK CHAIN TECHNOLOGY

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTHOSH KUMAR


"DESCRIPTION":

# Custom ERC-20 Token Smart Contract

## Overview
This project implements a custom ERC-20 token in Solidity. The contract follows the ERC-20 standard and allows minting an initial supply of tokens.

## Features
- Custom ERC-20 token named `CustomToken (CTK)`
- Follows the ERC-20 token standard
- Uses OpenZeppelin's ERC-20 contract for security
- Deployable on Ethereum testnets

## Smart Contract: `ERC20Token.sol`
### Functions
- `transfer(address _to, uint256 _value)`: Transfers tokens to another address.
- `approve(address _spender, uint256 _value)`: Allows an account to spend a specified number of tokens on behalf of the owner.
- `transferFrom(address _from, address _to, uint256 _value)`: Enables a third party to transfer tokens on behalf of the owner.
- `balanceOf(address _owner)`: Returns the token balance of the specified address.
- `totalSupply()`: Returns the total supply of tokens.

## Deployment Steps
1. Open [Remix IDE](https://remix.ethereum.org/).
2. Create a new file and paste the `ERC20Token.sol` code.
3. Compile the contract using Solidity 0.8.x compiler.
4. Deploy the contract using MetaMask on a test Ethereum network (Goerli, Sepolia, etc.).
5. Use Remix UI or Web3.js to interact with the contract.

## Example Transactions
- Deploy with an initial supply of `5000` tokens.
- Transfer `100` tokens to another account.
- Approve an account to spend `200` tokens.
- Use `transferFrom` to move `200` tokens on behalf of the owner.

## Dependencies
- Solidity ^0.8.0
- OpenZeppelin ERC-20 implementation
- MetaMask for Ethereum transactions
- Remix IDE or Hardhat for development

"OUTPUT":
  
  Task2:

  ![output2](https://github.com/user-attachments/assets/85c16e78-40c6-4e38-89c9-fc6c21af9477)

  

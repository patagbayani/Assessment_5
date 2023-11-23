# Assessment_5

# Overview
Welcome to MyToken, a simple ERC-20 token contract built on the Ethereum blockchain using the Solidity programming language. MyToken is designed to be a basic implementation of an ERC-20 token with additional functionalities such as token minting and burning, restricted to the contract owner.

# Features
ERC-20 Standard: MyToken follows the ERC-20 standard, providing compatibility with various decentralized applications (DApps), wallets, and exchanges that support ERC-20 tokens.

# Ownership Control: 
** The contract includes a modifier onlyOwner, ensuring that certain functions can only be executed by the contract owner.

# Initial Token Supply: 
** Upon deployment, MyToken mints an initial supply of 1,000,000 tokens with 18 decimals and assigns them to the contract owner.

# Minting Functionality: 
** The contract owner has the ability to mint new tokens and allocate them to a specified address using the mint function.

# Transfer and Burn: 
** Users can transfer tokens to other addresses using the standard ERC-20 transfer function. Additionally, the contract includes a burn function allowing token holders to burn (destroy) a specified amount of their own tokens.

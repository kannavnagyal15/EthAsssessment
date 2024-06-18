
MyToken Smart Contract
This repository contains a simple ERC20-like smart contract implemented in Solidity. The contract includes basic functionalities such as minting and burning tokens, and maintaining balances for different addresses.

Contract Details
Token Name: HARPIC
Token Abbreviation: HPC
Total Supply: Initially set to 0
Features
Public Variables

tokenName: Stores the name of the token.
tokenAbbrv: Stores the abbreviation of the token.
totalSupply: Stores the total supply of the token.
Mapping

balances: Maps addresses to their respective balances.

Mint Function
mint(address _address, uint _value): Increases the total supply of tokens and updates the balance of the specified address.

Burn Function
burn(address _address, uint _value): Decreases the total supply of tokens and updates the balance of the specified address, ensuring that the address has enough tokens to burn.

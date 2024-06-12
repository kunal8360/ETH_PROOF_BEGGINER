MyToken Smart Contract Overview This is a Solidity smart contract for a custom token named ARCEUS, with the abbreviation POKEMON. The contract allows for minting and burning of tokens, managing the total supply and individual balances of addresses.

Features Token Details:

Name: DragonGold Abbreviation: DRAGON Total Supply: Initially zero or undefined 

Token Balances:
The contract maintains a mapping of addresses to token balances. 

Minting:
The mint function increases the total token supply by a specified amount and adds that amount to the balance of the specified address. 

Burning:
The burn function decreases the total token supply by a specified amount and subtracts that amount from the balance of the specified address. Functions mint(address sender, uint256 amount): Mint new tokens and assign them to the specified address. burn(address sender, uint256 amount): Burn tokens owned by the specified address. 

Requirements Solidity Version: 0.8.25

Usage Deploy the contract on a compatible Ethereum Virtual Machine (EVM). Interact with the contract using a compatible Ethereum wallet or through smart contract function calls.

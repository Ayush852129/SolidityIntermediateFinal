

# DegenToken

DegenToken is an ERC20 token contract that implements additional functionality for purchasing items using the token.

## Features

- Minting of tokens: The contract owner can mint new tokens using the `mint` function.
- Purchasing items: Users can purchase items using their token balance by calling the `purchase` function.
- Burning tokens: Users can burn their tokens using the `burn` function.

## Contract Details

- Name: DegenToken
- Symbol: DGN
- Solidity Version: ^0.8.18
- License: MIT

## Usage

1. Deploy the DegenToken contract on an Ethereum network compatible with Solidity version ^0.8.18.
2. Mint initial tokens: As the contract owner, you can mint new tokens using the `mint` function. This can be done by calling the `mint` function and providing the recipient's address and the amount of tokens to be minted.
3. Purchasing items: Users can purchase items using their token balance. Each item is identified by an ID, and the `purchase` function is used to make a purchase. Provide the desired item ID as an argument to the `purchase` function.
4. Burning tokens: Users can burn their tokens by calling the `burn` function and specifying the amount of tokens to be burned.

Please refer to the contract's source code for detailed information about each function and its parameters.

## Dependencies

The contract relies on the following external dependencies:

- OpenZeppelin's ERC20 implementation: [@openzeppelin/contracts/token/ERC20/ERC20.sol](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol)
- OpenZeppelin's Ownable implementation: [@openzeppelin/contracts/access/Ownable.sol](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/access/Ownable.sol)

## Transactions

![Screenshot 2023-07-15 221417](https://github.com/Ayush852129/SolidityIntermediateFinal/assets/123191444/d05f5f36-6971-4202-a92d-38c121613362)


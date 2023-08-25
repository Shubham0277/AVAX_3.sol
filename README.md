# AVAX_3.sol

# MyToken (MTK) - ERC20 Token

## Overview

MyToken is an ERC20 token built on the Ethereum blockchain. This smart contract allows you to create, manage, and transfer tokens. It is designed to be simple and secure.

## Features

- **Minting:** Only the owner of the contract can mint new tokens. This is typically used for creating the initial token supply or adding tokens to the supply.

- **Burning:** Any token holder can burn their own tokens. This is irreversible and reduces the total supply.

- **Transfer:** Token holders can transfer their tokens to other addresses using standard ERC20 transfer functions.

## Getting Started

To deploy and interact with this contract, you can follow these steps:

1. **Deployment:** Deploy this contract to the Ethereum blockchain using a tool like Remix, Hardhat, or Truffle. Make sure you have sufficient ETH in your deploying account for gas fees.

2. **Mint Tokens:** As the owner, you can mint new tokens using the `mint` function by specifying the recipient's address and the amount of tokens to mint.

3. **Transfer Tokens:** Token holders can transfer tokens to other addresses using the standard ERC20 transfer functions.

4. **Burn Tokens:** Any token holder can burn their own tokens using the `burn` function.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


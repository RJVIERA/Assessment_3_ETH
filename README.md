# RJCoin - ERC20 Token Contract

This RJCoin smart contract is an ERC20 token implementation on the Ethereum blockchain. It provides functionalities for token minting, transferring, and burning, while enforcing ownership restrictions and maximum supply limits.

## Description

The RJCoin contract inherits from the ERC20 standard and extends it with additional features such as owner-only minting, transferability, and token burning. The contract also imposes a maximum supply limit to ensure token scarcity and enforce tokenomics.

## Usage

### Prerequisites

- Ensure you have an Ethereum wallet compatible with the Ethereum ecosystem, such as MetaMask.

### Deployment

1. Deploy the contract to the Ethereum blockchain using a suitable Ethereum development environment like Remix or Truffle.
2. Once deployed, the contract owner can interact with the contract to mint new tokens, transfer tokens to other addresses, and burn tokens.

## Functions

### mint

- **Description**: Allows the contract owner to mint new tokens and assign them to a specified address.
- **Parameters**:
  - `to`: The address to which the minted tokens will be assigned.
  - `value`: The amount of tokens to mint.
- **Conditions**:
  - Only the contract owner can initiate this function.
  - The total supply of tokens after minting must not exceed the maximum supply limit.
- **Events**:
  - None

### transfer

- **Description**: Allows any token holder to transfer tokens to another address.
- **Parameters**:
  - `to`: The address to which the tokens will be transferred.
  - `value`: The amount of tokens to transfer.
- **Conditions**:
  - None
- **Events**:
  - None

### burn

- **Description**: Allows any token holder to burn a specified amount of their tokens, thereby reducing the total supply.
- **Parameters**:
  - `value`: The amount of tokens to burn.
- **Conditions**:
  - None
- **Events**:
  - None

## Authors

The RJCoin contract was authored by RJ VIERA.

# Title:Smart Contract for MyToken: A Simple ERC-20 Token Implementation

# Overview / Description

This smart contract implements a basic ERC-20 token with functionalities for minting and burning tokens. It includes public variables for token details, a mapping for user balances, and functions to increase or decrease total supply and balances while enforcing balance constraints on burning.

# The contract includes the following key features:

Public Variables : Stores token details such as name, symbol, and total supply.

Balance Mapping : Maps addresses to their respective token balances.

Mint Function : Allows increasing the total supply and balance of a specified address.

Burn Function : Decreases total supply and balance of a specified address, with balance checks to ensure sufficient funds.

## Getting Started

To run and interact with this program, you can use Remix, an online Solidity Integrated Development Environment (IDE). Here are the steps to get started:

# Execution Instructions

To deploy and interact with the "Blockchain" contract using Remix, follow these steps:

## Step-by-Step Instructions

Go to the Remix Website:

=> Open https://remix.ethereum.org/

Create a New File:

=> Click on the "+" icon in the left-hand sidebar.

=> Name the file token.sol.

Copy and Paste the Solidity Code:

=>Copy the Solidity code provided link : (https://github.com/ShakilHossen537/token/blob/main/Token.sol) which is visible on github page.

=>Paste it into the newly created token.sol file in Remix.

Compile the Code:

=> Click on the "Solidity Compiler" tab in the left-hand sidebar.

=> Ensure the compiler version is set to 0.8.9 (or another compatible version).

=>Click on the "Compile project.sol" button.

Deploy the Contract:

=>Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.

=>Ensure the environment is set to "Remix VM (London)" or a suitable network.

=>Select the Bitcoin Cash contract from the dropdown menu.

=>Click on the "Deploy" button.

Interact with the Contract:

i) Mint Tokens:

=>In the deployed contract section, find the mint function.

=>Enter the recipient's address and the amount of tokens to mint.

=>Click on the transact button to mint tokens.

ii) Burn Tokens:

 =>Find the burn function.

 =>Enter the amount to burn.

 =>Click on the transact button to burn tokens.
 
Check Balances:

=> Enter an address into the balances function and click on the call button to see the balance.

View Token Details:

=> Click on the tokenName, tokenAbbrv, and totalSupply buttons to display their values.

By following these instructions, you can successfully deploy and interact with the "Blockchain" contract on the Ethereum blockchain using Remix.

* Authors
  
=> Sakil Hossen

Github : https://github.com/ShakilHossen537

# License

This project is licensed under the MIT License - see the link ( https://github.com/ShakilHossen537/token/blob/main/LICENSE ) for details.

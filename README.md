# ETH-AVAX-PROOF-Intermediate
Metacrafters Assignment
ETH + AVAX PROOF: Intermediate EVM Course
Projects that Metacrafters have assigned in the Blockchain course.

# Description
This repository contains the assignments
All the projects of this repository are related to the Blockchain written in Solidity and JavaScript (languages).

# Functions and Errors
In this module i have written a contract including the statements below-
require(): Used for validation and authorization checks. If the condition fails, reverts the transaction and provides a descriptive message.
revert(): Explicitly reverts the transaction and provides an optional message. Used for more general error handling scenarios.
assert(): Primarily for internal error checking and debugging. Should not be used for user-facing error messages.

# Smart Contract Management 
For this module i have created a contract using some functions called MyBank. Statements are explained below-
1. Ownership: The owner variable stores the contract's owner address.
2. Balance: The balance variable tracks the contract's available funds.
3. Constructor: Sets the initial owner to the contract deployer.
4. getBalance: Returns the current balance.
5. deposit: Accepts ETH payments and adds them to the balance.
6. onlyOwner modifier: Ensures only the owner can call functions with this modifier.
7. withdraw: Allows the owner to withdraw funds, with a balance check.

# Types of Functions
1. Contract Initialization:
Constructor Function: Sets the token's name and symbol during deployment, serving as its initial configuration.
2. Token Management-
Mint Function: Creates new tokens, increasing the total supply. Access is restricted to the contract owner using the onlyOwner modifier for security.
Burn Function: Destroys existing tokens, decreasing the total supply. Its visibility depends on specific use cases, potentially requiring access restrictions.
3. Token Transfers-
Transfer Function: Enables token movement between accounts, facilitating transactions within the token ecosystem.
4. Access Control-
Modifier: The onlyOwner modifier safeguards sensitive functions like minting, ensuring only the contract owner can execute them.

# Building on Avalanche
This is the final assignment of the course, i am showing my contract making DEGEN token on the Avalanche fuji testnet.
Executing the required and taught functions, and the user can mint, burn and transfer the token.
I am also able to show the verified transactions on the snowtrace explorer of Avalanche

# Getting Started
# Installing
There is no need to install any software, you can compile and run the code by visiting the given websites form your browser only.
# Executing program
To execute the code you can simply copy the code form the repository and then paste it too the compiler and then click on compile or run code.
* [Click here to run .js file](https://gitpod.io/workspaces/)
* [Click here to run .sol file](https://remix.ethereum.org/)
I have also provided my Loom video so that you can take the reference:

# Author
This smart contract is licensed under Jiffin Majo
Contact info:
Email: jiffinmack@gmail.com


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

Frontend Interaction-
1. Connect to Web3: Use a library like Web3.js to connect your frontend to the blockchain network.
2. Fetch Contract Address: Retrieve the deployed contract's address.
3. Create Contract Instance: Use Web3.js to create a contract instance for interaction.
4. Call Contract Functions: Use the contract instance to call functions like getBalance(), deposit(), and withdraw(), passing necessary parameters and handling responses.

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

# License
This smart contract is licensed under the MIT License.

# Author
Jiffin Majo

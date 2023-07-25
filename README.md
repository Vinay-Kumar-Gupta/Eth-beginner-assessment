# A Basic Eth Token Implementation
This repository contains a smart contract called "MyToken".This contract is written in remix IDE.
The contract allows for the creation, minting, and burning of tokens with the token name "VGTRONICS" and symbol "VG" (abbreviation). The contract uses the Ethereum blockchain and Solidity programming language.
The contract keeps track of the total supply and individual token balances for each address using a mapping structure.
This is a very basic program for learning purpose, those who want a solidity program as a sample they can prefer this repo.

# Discription
The VGTRONICS Token project is a basic implementation of an ERC20 token on the Ethereum blockchain. The smart contract allows users to create, mint, and burn tokens with the token name "VGTRONICS" and the symbol "VG."
Users can utilize the mint function to create new tokens and assign them to a specific address, effectively increasing the total supply. Conversely, the burn function allows token holders to reduce the total supply by burning a specific amount of their tokens.

# How and where to Run the Program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.
Now once you are on the remix IDE you need to create a new ".sol" file by clicking on the create new file icon.

After creating the file you need to specify the 
```solidity
// SPDX-License-Identifier: MIT
pragma solidity 0.8.18; //Version of solidity using
```
Now Write the remaining code after this, like declaring the variables and creating the functions like "mint" and "burn".

Now to run the code first you need to compile the code for that press `Ctrl+S` or you can compile the code by pressing the compile button in `solidity compiler` Tab on the left side of the IDE.

After compiling you need to deploy the contract by clicking the `deploy` button present in the `deploy & run transcations` tab.

At the bottom the you will find your contract running, there you will find all the public variables and functions, by clicking them and putting the values in the function you can get the output accordingly.

# Authors
@Vinay Kumar Gupta

# license
This project is licensed under the MIT License.




# Sol_advance_3

The following is a Anchor Framework program designed to perform Airdrop, Stake and Unstake tokens.

## Description

This is a smart contract implemented in Devnet using the Anchor framework. A client program is provided for testing and interacting with the smart contract.

## Getting Started

### Executing program

To run the program, please follow these steps:

`npm i`

and install yarn if getting error.

**Build**

`anchor build`

**Deploy**

`anchor deploy`

Once you have completed the above steps,

you can interact with the contract using the following command:

`anchor test`

It will run the staking.ts file and then all the three functions will be called 
which will create the accounts using program and then call the airdrop function two times, then it will stake tokens in both the possibilities and then unstake the 
same way which will also display the number in program logs.

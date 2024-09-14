# Turbin3BuildersCoursePrerequisites


## My Transactions

- Interacting with the program
https://explorer.solana.com/tx/4Ks7PQjyK9QYmcsHMumd52qeaGsPApWFjoH2LMx89MXYCwsXFccemdoJBf53bukGaqdBgeK9CUNengiecp53vtD3?cluster=devnet 

- Transferring funds
https://explorer.solana.com/tx/2qxvam6scUW1YMmrQZ8ekQZwuxKz8cBUc5LFqYrJK3H6LaTb3S4kKdzp2Cg3TGG9vjuPfuZxsC6dkAF7LwpwKJEY?cluster=devnet

- Getting devnet SOL
https://explorer.solana.com/tx/2caZnomYVE78GJtL8NNzgS8s4wJmhvFScGdu4BvDgGx9me6mCXoXsVT1Y6iPTeJ8YA7v7Xg4bfyFWe86HT7GapvH?cluster=devnet


## Scripts

- `yarn keygen`

Runs the script to generate a public key and secret key (keypair) via @solana/web3.js

- `yarn airdrop`

Runs the script to claim 2 SOL for the given wallet address (runs on devnet)

- `yarn transfer`

Runs the script to transfer all of a wallet's SOL balance to another wallet address. The script also contains another function that transfers a set amount instead.

- `yarn enroll`

Runs the script to interact with the WBA onchain program to enroll into the course. In short, it generates a PDA from the required seeds as well as passing in the user's Github username to the onchain program, which upon success, "enrolls" the user into the course.

- `yarn wallet-to-bs58`

Runs a script to convert a Solana wallet secret key (i.e. a byte array) into a base-58 encoded string.

- `yarn bs58-to-wallet `

Runs a script to convert a base-58 encoded private key into a Solana wallet secret key (i.e. a byte array).

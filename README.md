NFT Minting and Listing

This project is a simple implementation of an NFT minting system where NFTs can be created, 
stored, and listed. The NFTs contain metadata such as name, age, gender, and bling.

The application also allows you to view the total number of NFTs minted.

Features

Minting NFTs: Create NFTs with custom metadata.

List NFTs: Display the details of all minted NFTs.

Total Supply: Get the total number of NFTs minted so far.

Functions

mintNFT(_name, _age, _gender, _bling)

Parameters:

_name (string): The name of the NFT.

_age (number): The age of the NFT.

_gender (string): The gender associated with the NFT.

_bling (string): The bling type associated with the NFT.

Description: This function creates an NFT object with the given metadata and stores it in the NFTs array. 

A message is logged to the console to indicate the minting of the NFT.

listNFTs()

Description: This function loops through the NFTs array and prints each NFT's metadata (ID, name, age, gender, and bling) to the console.

getTotalSupply()

Description: This function prints the total number of NFTs that have been minted by displaying the length of the NFTs array.

How to Use

Mint an NFT: Call mintNFT() with the desired metadata parameters for the NFT (e.g., name, age, gender, and bling type).

List all NFTs: Call listNFTs() to print the details of each NFT to the console.

Get the Total Supply: Call getTotalSupply() to see the total number of NFTs minted so far.

# flow-mod-6

#CONTRACTS 

# CryptoPoops NFT Contract

## Overview

The CryptoPoops contract is an implementation of the Non-Fungible Token (NFT) standard in Cadence. It allows users to create, manage, deposit, and withdraw NFTs within their collections.

# Non-Fungible Token (NFT) Contract Interface

## Overview

The `NonFungibleToken` contract interface defines the structure and behavior of Non-Fungible Tokens (NFTs) in the Cadence programming language. Other NFT contracts will import and implement this interface to comply with the standard.

# Transaction: Initialize CryptoPoops Collection

## Description
This transaction initializes the CryptoPoops collection by creating an empty collection and linking it to a public capability. It ensures that the collection is stored in the account's storage and accessible to other accounts through the provided public capability.


# Transaction: Mint and Store NFT in Collection

## Description
This transaction mints a new NFT using the NFT minter from the CryptoPoops contract and stores it in the collection of the specified recipient. The recipient's account must have a Collection capability to receive the NFT.

## Parameters
- `recipient`: The address of the account where the newly minted NFT will be stored.


# Script: Retrieve NFT from Collection

## Description
This script retrieves an NFT from the specified account's collection using its unique ID.

## Parameters
- `account`: The address of the account that owns the collection.
- `id`: The unique ID of the NFT to retrieve from the collection.


#for any queries : 21021739@geu.ac.in

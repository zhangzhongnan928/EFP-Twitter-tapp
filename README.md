# EFP Twitter Tapp

## Overview

The EFP Twitter Tapp is a decentralized application (Tapp) that leverages the Ethereum Name Service Follow Protocol (EFP) and Basenames NFTs to create a Twitter-like following mechanism on the blockchain. This Tapp allows users to follow other users and generate shareable TLinks, all without requiring a centralized platform.

## Key Features

1. Follow other users using their Basename NFT
2. Generate shareable TLinks for easy distribution on social media

## Smart Contracts

The Tapp interacts with three main contracts:

1. EFPListNFT (ERC721)
2. ENSlistRecords
3. Basenames (ERC721)

## Functionality

### Following a User

Users can follow other users by interacting with the "follow" card. This card allows them to:

1. View the address of the Basename owner they want to follow
2. Initiate a transaction to follow the user

The following action is performed by calling the `applyListOp` function on the ENSlistRecords contract.

### Generating a TLink

Users can generate a TLink to share their profile using the "generateTLink" card. This feature:

1. Creates a unique TLink based on the user's address
2. Displays the generated TLink for easy copying and sharing

## TokenScript Implementation

The Tapp is implemented using TokenScript, which defines the structure and functionality of the Tapp. The main components of the TokenScript file are:

## Benefits

1. Decentralized following mechanism
2. Leverages existing Basenames NFTs
3. Easy to share and use on Twitter and other platforms
4. No additional services or products required beyond the TokenScript file

## Use Case

1. Basename NFT owners can create TLinks to share on Twitter
2. Other users can use these TLinks to follow the Basename owners
3. Creates a decentralized social graph based on blockchain interactions

This Tapp demonstrates the power of TokenScript in creating portable, decentralized applications that can integrate with existing social media platforms while leveraging blockchain technology.

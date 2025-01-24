# Lab Challenge: NFT Creation Using OpenSea Testnet and Sepolia

This project demonstrates the alternative process of creating NFTs on the OpenSea Testnet using the SepoliaETH Testnet due to changes in the NFT provider landscape that impacted initial deployment strategies.

## Table of Contents

1. [Project Description](#project-description)
2. [Alternative Implementation](#alternative-implementation)
3. [Steps to Completion](#steps-to-completion)
4. [Proof of Delivery](#proof-of-delivery)

## Project Description

Originally, the challenge was to create and list NFTs using OpenSea + Polygon and Upstick + IRIS. Due to restrictions and changes in provider mainnet requirements, this process was shifted to utilize the OpenSea Testnet with SepoliaETH for an equivalent outcome.

## Alternative Implementation

### Tools Used

- **OpenSea Testnet**: Employed for NFT creation and testing, simulating real-world trading environments.
- **SepoliaETH Testnet**: Used alongside MetaMask for transactions without incurring mainnet gas fees.

### Process Overview

- A new NFT collection is created on the OpenSea Testnet.
- A unique NFT item is then minted within this collection using SepoliaETH.
- All transactions and transfers utilize MetaMask configured for the Sepolia Test network.

## Steps to Completion

1. **OpenSea: Create Collection**
   - Navigate to the testnet's collection creation portal and set up a new collection, specifying name, themes, and any placeholder content.
   - **Collection Link**: _[LB DIO Lab](https://testnets.opensea.io/collection/lb-dio-lab)_

2. **OpenSea: Create NFT**
   - Within your collection, create a new NFT item by uploading artwork and adding metadata such as description and attributes.
   - Track the transaction on Etherscan to confirm minting.
   - **Item Link**: _[LB NFT 1 para curso NFT](https://testnets.opensea.io/assets/sepolia/0x2874f65022504a1cea53e1b4e821e0a4c0d28b72/1)_
   - **Etherscan Transaction**: _[0x2874f65022504a1cea53e1b4e821e0a4c0d28b72](https://sepolia.etherscan.io/address/0x2874f65022504a1cea53e1b4e821e0a4c0d28b72)_

3. **MetaMask: Import NFT**
   - Import the newly created NFT into MetaMask for easy management and future transfers.
   - Ensure MetaMask is connected to the Sepolia Testnet during the process.

4. **OpenSea: Transfer NFT to DIO Account**
   - Use OpenSea to initiate the transfer of the NFT to another account (e.g., DIO account).
   - Confirm transfer completion and log transaction details on Etherscan.
   - **Etherscan Transaction**: _[0x632dd8e3003c9bf8d5526e5db0549acc3b3d98a07bfb2fb76a925e489dd60545](https://sepolia.etherscan.io/tx/0x632dd8e3003c9bf8d5526e5db0549acc3b3d98a07bfb2fb76a925e489dd60545)_

## Proof of Delivery

This section includes steps and images documenting the completion of this lab challenge.

1. **OpenSea - Create Collection**:
  ![Create Collection - Metamask Confirmation](assets/1.1-opensea-create-collection.png)
  ![Create Collection Created](assets/1.2-opensea-create-collection.png)
  ![Create Collection - Etherscan](assets//1.3-etherscan-create-collection.png)

2. **OpenSea - Create NFT**:
  ![Create NFT](assets/2.1-opensea-create-nft.png)
  ![Create NFT - Metamask Confirmation](assets/2.2-metamask-create-nft-confirm.png.png)
  ![NFT Created](assets/2.3-opensea-create-nft-created.png.png)
  ![Create NFT - Etherscan](assets/2.4-etherscan-create-nft.png)

3. **OpenSea - List for Sale NFT**:
  ![List for Sale](assets/3.1-opensea-list-for-sale.png)
  ![List for Sale2](assets/3.2-opensea-list-for-sale.png)
  ![List for Sale3](assets/3.3-opensea-list-for-sale.png)
  ![List for Sale - Metamask Confirmation](assets/3.4-metamask-list-for-sale-confirm.png)
  ![List for Sale - Listed](assets/3.5-opensea-list-for-sale-listed.png)
  ![List for Sale - Item Info](assets/3.6-opensea-list-for-sale-item.png)

4. **Metamask - Import NFT**:
  ![Import NFT MetaMask](assets/4.1-metamask-nft.png)
  ![Import NFT MetaMask - Import Manually](assets/4.2-metamask-nft-import-manually.png)
  ![Import NFT MetaMask - Imported](assets/4.3-metamask-nft-imported.png)
  ![Import NFT MetaMask - Details](assets/4.4-metamask-nft-details.png)

5. **OpenSea - Transfer NFT**:
  ![Transfer NFT](assets/5.1-opensea-send-nft.png)
  ![Transfer NFT - Metamask Confirmation](assets/5.2-metamask-send-nft-confirm.png)
  ![Transfer NFT - Complete](assets/5.3-opensea-send-nft-complete.png)
  ![Transfer NFT - Etherscan](assets/5.4-etherscan-send-nft.png)
  ![Transfer NFT - Previously Owned](assets/5.5-opensea-send-nft-previously-owned.png)


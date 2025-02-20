# Project name: diary-contract
Description: diary smart contract blockchain

# Blockchain Diary Smart Contract

##**Smart contract address:** 0x490403804D07FA629689Ae7dAC866c9f55Cc325F

## Overview
The Blockchain Diary is a simple Ethereum-based smart contract allowing users to securely record diary entries on the blockchain. Each entry is timestamped and stored immutable, ensuring data integrity and ownership.

## Features
- Users can add diary entries that are timestamped automatically.
- Each user’s entries are stored privately within the contract.
- Users can retrieve their total entry count.
- Users can fetch specific diary entries using an index.

## Smart Contract Functions
### `addEntry(string memory _content)`
Adds a new diary entry with the given content. The entry is timestamped using `block.timestamp`.

### `getEntriesCount() public view returns (uint256)`
Returns the number of diary entries the caller has recorded.

### `getEntry(uint256 index) public view returns (uint256, string memory)`
Retrieves a specific diary entry by index. Returns the timestamp and content of the entry.

## Usage
1. Deploy the contract on an Ethereum-compatible blockchain.
2. Interact with the contract through a blockchain explorer or a front-end UI.
3. Use the provided functions to add and retrieve diary entries.

## License
This project is open-source and available under the MIT License.


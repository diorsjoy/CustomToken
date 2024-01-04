# CustomToken - ERC20 Token with Additional Features

## Overview
The `CustomToken` contract is an ERC20 token implementation on the Ethereum blockchain. It allows users to create and manage custom tokens with a specified name, symbol, and decimal places. In addition to standard ERC20 functionalities, this contract includes features to retrieve the latest transaction timestamp and the addresses of the transaction sender and receiver.

## Contract Details

- **Name:** AITU_Alina
- **Symbol:** AITA
- **Decimals:** 18
- **Total Supply:** 2000 AITA tokens

## Features

### ERC20 Standard Functionalities
1. **Balance Inquiry:**
    - Function: `balanceOf(address tokenOwner)`
    - Purpose: Retrieve the token balance of a specific address.

2. **Allowance Inquiry:**
    - Function: `allowance(address tokenOwner, address spender)`
    - Purpose: Retrieve the remaining allowance that the owner has granted to a specific spender.

3. **Approval:**
    - Function: `approve(address spender, uint256 tokens) returns (bool success)`
    - Purpose: Approve a specific amount of tokens to be spent by another address.

4. **Token Transfer:**
    - Function: `transfer(address to, uint256 tokens) returns (bool success)`
    - Purpose: Transfer tokens from the sender's address to the specified recipient.

5. **Transfer with Approval:**
    - Function: `transferFrom(address from, address to, uint256 tokens) returns (bool success)`
    - Purpose: Transfer tokens from one address to another, using prior approval.

### Additional Features
1. **Latest Transaction Timestamp:**
    - Function: `getLatestTransactionTimestamp() returns (uint256)`
    - Purpose: Retrieve the timestamp of the latest transaction.

2. **Transaction Sender:**
    - Function: `getTransactionSender() returns (address)`
    - Purpose: Retrieve the address of the sender of the current transaction.

3. **Transaction Receiver:**
    - Function: `getTransactionReceiver() returns (address)`
    - Purpose: Retrieve the contract's address as the receiver of the current transaction.

## Usage
<img width="852" alt="image" src="https://github.com/diorsjoy/CustomToken/assets/113359068/0285a222-da3e-4f76-8a5f-1e21299fb700">
<img width="840" alt="image" src="https://github.com/diorsjoy/CustomToken/assets/113359068/a463568a-c48f-4ae5-b765-11fc3716bd6a">
<img width="687" alt="image" src="https://github.com/diorsjoy/CustomToken/assets/113359068/bbb13c18-3954-4b1e-9dae-2d8fc0630e15">
<img width="1356" alt="image" src="https://github.com/diorsjoy/CustomToken/assets/113359068/f2474b99-07a1-46f7-a865-37069c37cb61">

## License
This project is licensed under the MIT License - see the LICENSE file for details.

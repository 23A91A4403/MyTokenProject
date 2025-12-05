\# MyToken (MTK)



\## Overview

MyToken is a simple ERC-20 compatible token built on Ethereum for learning purposes.  

This project demonstrates the basics of creating your own cryptocurrency token using Solidity and RemixIDE.



\## Token Details

\- \*\*Name\*\*: MyToken

\- \*\*Symbol\*\*: MTK

\- \*\*Decimals\*\*: 18

\- \*\*Total Supply\*\*: 1,000,000 MTK



\## Features

\- ✅ Standard ERC-20 implementation

\- ✅ Transfer tokens between addresses

\- ✅ Approve and transferFrom functionality

\- ✅ Event emission for transparency

\- ✅ Balance tracking



\## How to Deploy

1\. Open \[RemixIDE](https://remix.ethereum.org/).

2\. Create a new file called `MyToken.sol`.

3\. Paste your ERC-20 contract code into the file.

4\. Compile the contract using \*\*Solidity 0.8.x\*\*.

5\. Go to the \*\*Deploy \& Run Transactions\*\* tab.

6\. Select \*\*JavaScript VM\*\* as the environment.

7\. Enter your \*\*initial supply\*\* in the constructor (e.g., `1000000000000000000000000` for 1 million tokens with 18 decimals).

8\. Click \*\*Deploy\*\*.

9\. The deployed contract will appear under \*\*Deployed Contracts\*\*.



\## How to Use

```solidity

// Check Balance

balanceOf(address) → returns uint256



// Transfer Tokens

transfer(address to, uint256 amount) → returns bool



// Approve Spending

approve(address spender, uint256 amount) → returns bool



// Transfer on Behalf

transferFrom(address from, address to, uint256 amount) → returns bool

```
## Screenshots

### 1. Compilation Success
![Compilation](screenshots/CompilationOfMyToken.sol.png)

### 2. Deployment
![Deployment](screenshots/Deployed_Contracts(1).png)

### 3. Token Info (name, symbol, decimals, total supply)
![Token Info](screenshots/Deployed_Contracts(Name).png)
![Token Info](screenshots/Deployed_Contracts(Symbol).png)
![Token Info](screenshots/Deployed_Contracts(decimal).png)
![Token Info](screenshots/Deployed_Contracts(totalSupply).png)
![Token Info](screenshots/getTokenInfo.png)
![Token Info](screenshots/getTotalSupply.png)
![Token Info](screenshots/BalanceOf.png)



### 4. Transfer Test
![Transfer](screenshots/TRANSFER.png)

### 5. Approve & TransferFrom Test
![Approve](screenshots/APPROVE.png)
![Token Info](screenshots/TRANSFERFORM.png)






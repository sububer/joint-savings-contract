# joint-savings-contract
Joint savings account smart contract using solidity.

---

## Overview
A [Solidity](https://docs.soliditylang.org/en/v0.8.13/) smart contract was authored to model a [joint savings account](/app/joint_savings.sol). [Screenshots](/ExecutionResults/) were taken of the contract execution and log output.   

See [installation](#installation) and [usage](#usage) below for specifics.  

---

## Process
[JointSavings](./app/joint_savings.sol) will use [Solidity](https://docs.soliditylang.org/en/v0.8.13/), and [Remix Ethereum IDE](https://remix-ide.readthedocs.io/en/latest/#).  

**High-level steps:**  
1. Create a [Joint Savings Account](./app/joint_savings.sol) smart contract using [Solidity](https://docs.soliditylang.org/en/v0.8.13/)
2. Compiile and Deploy the [contract](./app/joint_savings.sol) using [Remix IDE](https://remix-ide.readthedocs.io/en/latest/#)
3. Interact with the deployed smart contract and capture output to screenshots.  

**Submission:**  
- completed [Joint Savings Account](./app/joint_savings.sol) smart contract
- [Screenshots](./ExecutionResults/) confirming deposit/withdrawl transactions are working as expected

## Some Contract Execution Screenshots

See all screenshots in [ExecutionResults](./ExecutionResults/) folder.  

**setAccounts**
![SetAccounts](/ExecutionResults/01_set_accounts.png)  

**deposit**
![deposit 10 eth](/ExecutionResults/03_deposit_10_ether_as_wei.png)  

**withdraw**
![withdraw 10 eth to account2](/ExecutionResults/07_withdraw_10eth_to_account2.png)  

**lastToWithdraw**
![lastToWithdraw](/ExecutionResults/08_lastToWithdraw_output.png)  

**lastWithdrawAmount**
![lastWithdrawAmount](/ExecutionResults/09_lastWithdrawAmount_output.png)  



---

## Technologies

This challenge uses:  
- [Solidity](https://docs.soliditylang.org/en/v0.8.13/)
- [Remix Ethereum IDE](https://remix-ide.readthedocs.io/en/latest/#)
- [Ganache](https://trufflesuite.com/ganache/)  

See [installation](#installation) and [usage](#usage) below for specifics.

---

## Installation

**Ganache**  
Docs and download Ganache from [Ganache](https://trufflesuite.com/ganache/)  

---

## Usage

1. Load the [contract](./app/joint_savings.sol) into the Remix IDE.
2. Compile contract
3. Deploy to either javascript vm or local web3 address provider like ganache
4. Execute deployed contract functionality via the remix IDE  

---

## Contributors

[David Lopez](https://github.com/sububer)

---

## License

MIT
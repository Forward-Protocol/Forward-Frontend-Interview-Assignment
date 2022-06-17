# Forward Frontend Interview Assignment

## Overview

The assignment's purpose is to test the candidates abilty to develop a web applcation by following the provided design and how code were written will also be considered.

There are two tasks. The first task is about basic understanding of React. The second task is optional, it is about web3.

There will be 7 days timeframe to finish the assignment, once it finish send me the private github repository to phaisan@forward.market.

## Requirement

The project wil be required to used the following frameworks:

- React
- TypeScirpt

Follow the design in Figma:
[Link to Figma](https://www.figma.com/file/mWAkTDABZSqC0Zynyh4alA/Forward-Frontend-Interview-Assignment?node-id=6%3A170)

_Note: Except the above requirement, Feel free to use any tools and libraries

## Task

### 1. Sortable Table

- [ ] Connect API to fetch data and display on the table [API](https://testnet.forward-hq.ml/api/coins/)
- [ ] Sortable table: using table header to select between ascending and descending order.
- [ ] Filter/Search function for table
- [ ] Favourite feature: the favourite need to be saved(local storage).

_Note: Please keep preformance in mind

### 2. Basic Web3 (optional)

The candidates must use the BSC testnet for this task.

#### &nbsp; Part 1: Connect Wallet

- [ ] Connect Wallet
- [ ] Display wallet address
- [ ] Display wallet balance(BNB)

#### &nbsp; Part 2: Smart Contract Interaction

&nbsp; Using the contract to Deposit/Withdraw and also display APR and deposited balance.

- [ ] Deposit function (BNB) (use function ```mintWithEther``` in smart contract)
- [ ] Withdraw function (BNB) (use function ```burnToEther``` in smart contract)
- [ ] Display deposited balance (read from function ```balanceOf```)
- [ ] Display APR
- [ ] Deposit/Withdraw using WBNB

```javascirpt
  CONTRACT_ADDRESS = '0xf8e86a665c905cE1798b4d0F92C146959312Af79';
  ABI = 'constants/abi/contractABI.json'
```

---

If there are any question, feel free to contract me at phaisan@forward.market

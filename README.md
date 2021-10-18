Required global libraryyyyyyy
========================
1. truffle
2. ganache-cli

```code
npm install -g ganache-cli truffle
```




Install library 
===============

```code
  npm install
```



Run Unit Test 
===============

```code
  truffle test
```




Deployment Networks
====================

** Required to run local blockchain(ganache-cli) before deploy

```code
  # open new terminal
  ganache-cli
```


```code
# deploy smart contract
 truffle migrate --network develop
```

|  Networks | Required    |
|-----------|------------|
| develop   |      |
| testnet   |   .secret   |
|  bsc      |   .secret   |

**.secret** files, store mnemonic 12 words




Documents
=========
1. [Interacting with Smart Contract](https://www.trufflesuite.com/docs/truffle/getting-started/interacting-with-your-contracts)

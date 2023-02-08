# TON Blockchain: Simple Counter Func Smart Contract Example

## Installation

Ensure you are using Node 16 (or higher) and you have installed all dependencies using `npm` like so:

```
npm i
```

## Compile

Compile the contract using `func-js` like so:

```
npx func-js stdlib.fc counter.fc --boc counter.cell
```

## Deploy

Use [this wallet](https://testnet.tonscan.org/address/EQBO_BKSeVRZzRhfuj3hqF-ez4g3T0af7xXCk0cve35ps83v).

```
EQBO_BKSeVRZzRhfuj3hqF-ez4g3T0af7xXCk0cve35ps83v
```

Deployment output:

```
➜  counter npx ts-node deploy.ts

contract address: EQCDXF1vlR6BOlpsr4ZZKVLMPTcTZLxbtgz7ieiHayryu_C2
waiting for deploy transaction to confirm...
deploy transaction confirmed!
```
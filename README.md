# Udacity Blockchain Capstone

The capstone will build upon the knowledge you have gained in the course in order to build a decentralized housing product.

## Launch Ganache:

Run this command in separate terminal window

`npx ganache-cli -m "candy maple cake sugar pudding cream honey rich smooth crumble sweet treat"`

## Run truffle tests:

`npm install`

`cd eth-contracts`

`truffle test ./test/TestERC721Mintable.js`

`truffle test ./test/TestSquareVerifier.js`

`truffle test ./test/TestSolnSquareVerifier.js`

## Deploy contracts to Rinkeby network

Commands:

`export INFURA_KEY="<your_infura_key>"`

`export MNEMONIC="<metamask>"`

`export NETWORK="rinkeby"`

`truffle deploy --network rinkeby`

Result:

```
  Verifier: 0xe5D5E43337BfDB07394d9132962a3E3b2A5e4B64
  SolnSquareVerifier: 0x3253ffBEaef51FEe7bE8fCb64ED4a89E06cfc5F7
```

## SolnSquareVerifier ABI

SolnSquareVerifier Contract ABI place [here](https://github.com/dexterpuru/real-estate-enterprice/blob/master/eth-contracts/build/contracts/SolnSquareVerifier.json)

Tokens minted with [myetherwallet tool](https://www.myetherwallet.com/interface/interact-with-contract)

OpenSea Rinkeby marketplace [link](https://rinkeby.opensea.io/assets/niktokenname)

# Project Resources

- [Remix - Solidity IDE](https://remix.ethereum.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Truffle Framework](https://truffleframework.com/)
- [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
- [Open Zeppelin ](https://openzeppelin.org/)
- [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
- [Docker](https://docs.docker.com/install/)
- [ZoKrates](https://github.com/Zokrates/ZoKrates)

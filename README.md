# ERC 1155 NFT Smart-Contract Template

Use this contract for saving gas fees on Ethereum NFT launches, not only for NFT with multiple copies of the same item.

## Functions

* Whitelist
* Presale
* Change Base-URI (meta-reveal)
* Batch Mint
* Extensible: Create fungible tokens in the same contract (not included). 

## Development

First clone this repository and enter the directory.

Install dependencies:

```
$ yarn
```

## Testing

We use [Hardhat](https://hardhat.dev) and [hardhat-deploy](https://github.com/wighawag/hardhat-deploy)

To run integration tests:

```sh
$ yarn test
```

To run coverage:

```sh
$ yarn coverage
```

To deploy to Rinkeby:
create a secretManager.js containing the required private keys(see secretsManager.example.js) then run:

```sh
$ yarn deploy:network rinkeby
```

To verify the contract run:

```sh
$ yarn verify:network rinkeby [CONTRACT-ADDRESS] [arg1]
```

## For additional testing verified versions of a mock ERC721 token and a mock ERC20 token are available at:

## Test Coverage

## Expected Gas Costs

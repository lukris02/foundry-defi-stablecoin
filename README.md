# Foundry DeFi Stablecoin

## Description
An exogenous algorithmic stablecoin pegged to USD. For collateral, the protocol accepts wETH and wBTC.

## Topics
Solidity, Foundry, OpenZeppelin ERC20, ERC20Burnable, Ownable, ReentrancyGuard, Chainlink Price Feeds, Fuzz and Invariant Testing

# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [foundry](https://getfoundry.sh/)

## Quickstart

```
git clone https://github.com/lukris02/foundry-defi-stablecoin
cd foundry-defi-stablecoin
forge build
```

## Deploy

This will default to your local node. You need to have it running in another terminal in order for it to deploy.

```
make deploy
```

## Testing

```
forge test
```

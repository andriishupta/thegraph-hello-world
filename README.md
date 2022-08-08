# Lens Protocol SubGraph - "Hello World"

This project is created for testing Lens Protocol on TheGraph

## Development
No simple way to have dev environment, so flow is: implement events and deploy to real HostedSubgraph

## Deploy
To be authed and run:

`yarn deploy`

## Structure

Currently, it contains default folders to TheGraph initial project with additional `hardhat` setup

### Hardhat and `/contracts`
I have added Events and DataTypes from lens-protocol [source code](https://github.com/aave/lens-protocol/tree/main/contracts/libraries),
because **LensHub** contract's abi doesn't include those as libraries

Generated artifacts are manually transferred to `/abis`

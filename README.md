# USDC Multi-Hopping Demonstration - ProtoCCTP (Foundry)

This repository is a demonstration of the ProtoCCTP feature, which enables Multi-Hopping of USDC tokens across multiple CCTP enabled blockchains. It showcases the VIA Labs' USDC Multi-Hop functionality, allowing users to send USDC from a source chain to a final recipient on a destination chain, traversing multiple intermediary chains.

Built using Foundry, a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.

## Overview

**USDCHop** enables users to send **USDC** from one blockchain to another using a predetermined path of chains, ultimately delivering the tokens to the specified final recipient. The transfer of USDC hops from one chain to another until it reaches its destination.

### Features:
- **Cross-chain USDC Transfers**: Initiate a USDC transfer on a source chain and send it across multiple chains until it reaches the destination chain and the final recipient.
- **Customizable Path**: Specify the exact path of chains through which the USDC should be transferred.

This repository demonstrates the **VIA Labs USDC Feature** and the **ProtoCCTP** framework.

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```

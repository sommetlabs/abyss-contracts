# Abyss Contracts

Open-source [Compact](https://docs.midnight.network/compact) smart contracts developed by [Sommet Labs](https://sommet.digital) for the [Midnight](https://midnight.network) network.

These contracts power [abyss.trade](https://abyss.trade) and are published for the broader Midnight developer community to use, extend, and build upon.

## Contracts

| Contract | Description | Status |
|----------|-------------|--------|
| [FungibleTokenUTXO](mips/mip-Fungible-Token-Standard-with-UTXO-Conversion-Extensions.md) | Fungible token standard with bidirectional UTXO conversion (shield/unshield) | MIP Proposed |

## Overview

Midnight's [dual-ledger architecture](https://docs.midnight.network/concepts/ledgers) supports both account-based (Map) and UTXO-based token representations. The contracts in this repository bridge these two models, enabling tokens to participate in [Zswap](https://docs.midnight.network/concepts/zswap) atomic swaps, privacy-enhanced transfers, and other UTXO-native operations while preserving the familiar account-based interface for DeFi logic.

All contracts are built on top of the [OpenZeppelin Compact Contracts](https://github.com/OpenZeppelin/compact-contracts) library.

## Structure

```
mips/          MIP specifications
contracts/     Compact source code (coming soon)
tests/         Integration and unit tests (coming soon)
```

## License

Apache-2.0

# Awesome Omni [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources related to Omni, the interop blockchain for Ethereum rollups.

## Contents

- [Resources](#resources)
- [Templates](#templates)
- [Examples](#examples)
- [Contribute](#contribute)

## Resources

Official links, developer tools, documentation, and other learning resources.

- [Official Website](https://omni.network/) - Find general information and the latest updates on Omni.
- [Developer Documentation](https://docs.omni.network/) - Comprehensive developer resources, including API references and setup guides.
- [Github Monorepo](https://github.com/omni-network/omni) - The official GitHub repository for Omni core implementations.

## Templates

Templates to help you start building on Omni.

- [Basic Rollup Template](https://github.com/omni-network/omni-forge-template) - A starter template with an `XGreeter` cross-chain set string contract that emits an event.

## Examples

Practical examples and tutorials to understand how to work with Omni.

- [Cross Chain Staking](https://github.com/omni-network/cross-stake) - Example cross chain app for multi-rollup staking with global state managed by the Omni EVM.
- [XRegistry Contract](https://github.com/omni-network/omni/blob/main/contracts/src/xchain/XRegistry.sol) - A contract address registry that syncs registrations across [XRegistryReplicas](https://github.com/omni-network/omni/blob/main/contracts/src/xchain/XRegistryReplica.sol) on other chains.
  - [PortalRegistry Contract](https://github.com/omni-network/omni/blob/main/contracts/src/xchain/PortalRegistry.sol) - Omni contract to register supported portals across the Ethereum rollup ecosystem.

## Contribute

Contributions are welcome! If you want to contribute to the repository, please read the [contribution guidelines](contributing.md) first.


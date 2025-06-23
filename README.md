# Awesome EIP-7702 Delegations

![](https://github.com/user-attachments/assets/8883852d-ddf1-4d5b-8b47-b0173459d6ff)

A curated list of awesome [EIP-7702](https://eips.ethereum.org/EIPS/eip-7702) delegation destinations. 

> This list is intended to aggregate and spread the knowledge of the best delegation practices out there. Contributions are warmly welcome. If anything is missing, please don't hesitate to open a pull request.

## Resources

|         Resource        |          Tags         |       Description       |
|-------------------------|-----------------------|-------------------------|
| [BEBE by Vectorized](https://github.com/Vectorized/bebe) | Statelessness, Hyperoptimization | A basic stateless [ERC-7821](https://eips.ethereum.org/EIPS/eip-7821) style batch executor contract for EOAs to delegate to. |
| [Simple EIP-7702 Account from Infinitism](https://github.com/eth-infinitism/account-abstraction/blob/develop/contracts/accounts/Simple7702Account.sol) | [ERC-4337](https://eips.ethereum.org/EIPS/eip-4337) | A minimal account to be used with EIP-7702 (for batching) and ERC-4337 (for gas sponsoring). |
| [All-in-one Account from Ithaca](https://github.com/ithacaxyz/account) | PassKeys, Gas Sponsorship, Session Keys | All-in-one EIP-7702 powered account contract, coupled with Porto. |
| [Experimental Delegation with P256 Authorization](https://github.com/ithacaxyz/exp-0001) | Authorization, P256 | An experimental delegation contract with basic P256 authorization & batch call capabilities. |
| [Smart Contract Wallet from Uniswap](https://github.com/Uniswap/calibur) | Singleton, Authorization, ERC-4337 | A singleton contract wallet supporting batched transactions, alternative signers, and native ETH `transferFrom`. |
| [Simple Vyper Smart Wallet by Fubuloubu](https://github.com/fubuloubu/Purse) | Vyper, Plugins | A (very) simple smart wallet for EOAs, using EIP-7702 for core functionality. |
| [Ultimate Smart Account from OpenFort](https://github.com/openfort-xyz/openfort-7702-account) | ERC-4337, Session Keys, Recovery | All-in-one EIP-7702 powered smart account with session key support. |
| [Smart Contract Wallet from OKX](https://github.com/okx/wallet-core) | Sessions, Relayers | A modular and secure implementation of EIP-7702 smart contract wallet. |
| [ERC-1967 Proxy for Smart Accounts from Base](https://github.com/base/eip-7702-proxy) | Proxy, [ERC-1271](https://eips.ethereum.org/EIPS/eip-1271) | A secure [ERC-1967](https://eips.ethereum.org/EIPS/eip-1967) proxy implementation for EIP-7702 smart accounts. |
| [EIP-7702 Proxy from Solady](https://github.com/Vectorized/solady/blob/main/src/accounts/EIP7702Proxy.sol) | Proxy, Hyperoptimization | Relay proxy for upgradeable EIP-7702 accounts without the need for redelegation. |
| [ERC-1967 Proxy with EIP-7702 Initialization from OpenFort](https://github.com/openfort-xyz/openfort-contracts/blob/feat/eip-7702/contracts/core/upgradeable/UpgradeableOpenfortProxy7702.sol) | Proxy | ERC-1967 Proxy with EIP-7702 Initialization Support. |

## Disclaimer

A star to the repo would be awesome.

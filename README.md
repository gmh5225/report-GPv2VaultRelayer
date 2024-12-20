# GPv2VaultRelayer

## Contract Information
- **Contract Name:** GPv2VaultRelayer
- **Compiler Version:** v0.7.6+commit.7338295f
- **Optimization Enabled:** Yes with 1000000 runs
- **Contract Address:** 0xC92E8bdf79f0507f65a392b0ab4667716BFE0110
- **EVM Version:** default
- **Chain:** Ethereum Mainnet
- **Creator:** 0x7eabac82da8ea6ac980d619cb562a9924d1e3baa
- **Creation Transaction:** 0xf49f90aa5a268c40001d1227b76bb4dd8247f18361fcad9fffd4a7a44f1320d3

## Source Code Structure
```
└── src
    └── contracts
        └── GPv2AllowListAuthentication.sol
        └── interfaces
            ├── GPv2Authentication.sol
            ├── IERC20.sol
            ├── IVault.sol
            ├── GPv2EIP1271.sol
        └── libraries
            ├── GPv2EIP1967.sol
            ├── GPv2Interaction.sol
            ├── GPv2Order.sol
            ├── GPv2Trade.sol
            ├── GPv2Transfer.sol
            ├── SafeCast.sol
            ├── SafeMath.sol
            ├── GPv2SafeERC20.sol
        └── mixins
            ├── Initializable.sol
            ├── StorageAccessible.sol
            ├── GPv2Signing.sol
            ├── ReentrancyGuard.sol
        └── test
            ├── GPv2AllowListAuthenticationV2.sol
            ├── GPv2AllowListAuthenticationTestInterface.sol
            ├── SmartSellOrder.sol
            ├── NonStandardERC20.sol
            ├── GPv2SafeERC20TestInterface.sol
            ├── GPv2TradeTestInterface.sol
            ├── GPv2SigningTestInterface.sol
            ├── StateChangingERC1271.sol
            ├── GPv2OrderTestInterface.sol
            ├── GPv2TransferTestInterface.sol
            ├── GPv2SettlementTestInterface.sol
            ├── GPv2InteractionTestInterface.sol
        └── GPv2Settlement.sol
        └── GPv2VaultRelayer.sol

```
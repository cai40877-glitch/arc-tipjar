# arc-tipjar

Creator USDC tip jar on Arc testnet.

- Chain ID: `5042002`
- RPC: `https://rpc.testnet.arc.network`
- USDC: `0x3600000000000000000000000000000000000000`
- Explorer: https://testnet.arcscan.app

## Contract

`src/TipJar.sol` records USDC payments and emits accounting events.

## Build

```bash
forge build
```

## Deployment

- Contract: `0x551b34d4c05cD3F5e10Dc474B9b9fCAA4fE61785`
- Tx: `inferred-from-nonce`
- Explorer: https://testnet.arcscan.app/address/0x551b34d4c05cD3F5e10Dc474B9b9fCAA4fE61785

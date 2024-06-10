---
layout: docs
sidebar: false
toc_max_heading_level: 5
---

```ts
type CreateTokenBridgeResults: object;
```

## Type declaration

| Member | Type | Description |
| :------ | :------ | :------ |
| `retryables` | [`WaitForRetryablesResult`](../../createTokenBridgePrepareTransactionReceipt/type-aliases/WaitForRetryablesResult.md) | Retryable transaction receipts of createTokenBridgePrepareTransactionReceipt ([WaitForRetryablesResult](../../createTokenBridgePrepareTransactionReceipt/type-aliases/WaitForRetryablesResult.md)) |
| `setWethGateway` | `object` | Optional: createTokenBridgePrepareSetWethGatewayTransaction's result |
| `setWethGateway.retryables` | [`TransactionReceipt`] | Retryable transaction receipt of createTokenBridgePrepareSetWethGatewayTransactionReceipt ([WaitForRetryablesResult](../../createTokenBridgePrepareTransactionReceipt/type-aliases/WaitForRetryablesResult.md)) |
| `setWethGateway.transaction` | `Transaction` | Transaction of createTokenBridgePrepareSetWethGatewayTransactionReceipt (Transaction) |
| `setWethGateway.transactionReceipt` | [`CreateTokenBridgeSetWethGatewayTransactionReceipt`](../../createTokenBridgePrepareSetWethGatewayTransactionReceipt/type-aliases/CreateTokenBridgeSetWethGatewayTransactionReceipt.md) | Transaction receipt of createTokenBridgePrepareSetWethGatewayTransactionReceipt ([createTokenBridgePrepareSetWethGatewayTransactionReceipt](../../createTokenBridgePrepareSetWethGatewayTransactionReceipt/functions/createTokenBridgePrepareSetWethGatewayTransactionReceipt.md)) |
| `tokenBridgeContracts` | [`TokenBridgeContracts`](../../types/TokenBridgeContracts/type-aliases/TokenBridgeContracts.md) | Core token bridge contracts ([TokenBridgeContracts](../../types/TokenBridgeContracts/type-aliases/TokenBridgeContracts.md)) |
| `transaction` | `Transaction` | Transaction of createTokenBridgePrepareTransactionRequest |
| `transactionReceipt` | [`CreateTokenBridgeTransactionReceipt`](../../createTokenBridgePrepareTransactionReceipt/type-aliases/CreateTokenBridgeTransactionReceipt.md) | Transaction receipt of createTokenBridgePrepareTransactionReceipt ([CreateTokenBridgeTransactionReceipt](../../createTokenBridgePrepareTransactionReceipt/type-aliases/CreateTokenBridgeTransactionReceipt.md)) |

## Source

[src/createTokenBridge.ts:51](https://github.com/OffchainLabs/arbitrum-orbit-sdk/blob/9d5595a042e42f7d6b9af10a84816c98ea30f330/src/createTokenBridge.ts#L51)
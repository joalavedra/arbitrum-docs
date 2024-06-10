---
layout: docs
sidebar: false
toc_max_heading_level: 5
---

```ts
function ethersTransactionReceiptToViemTransactionReceipt(receipt: TransactionReceipt): ViemTransactionReceipt
```

Converts an Ethereum transaction receipt (from `EthersTransactionReceipt`) to
a Viem transaction receipt (to `ViemTransactionReceipt`). This function maps
the fields from the Ethereum receipt to the corresponding fields in the Viem
receipt, including conversion of data types where necessary.

## Parameters

| Parameter | Type |
| :------ | :------ |
| `receipt` | `TransactionReceipt` |

## Returns

`ViemTransactionReceipt`

## Source

[src/ethers-compat/ethersTransactionReceiptToViemTransactionReceipt.ts:33](https://github.com/OffchainLabs/arbitrum-orbit-sdk/blob/9d5595a042e42f7d6b9af10a84816c98ea30f330/src/ethers-compat/ethersTransactionReceiptToViemTransactionReceipt.ts#L33)
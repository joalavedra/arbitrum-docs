---
id: "ArbitrumProvider"
title: "Class ArbitrumProvider"
sidebar_label: "ArbitrumProvider"
sidebar_position: 0
custom_edit_url: null
---

Arbitrum specific formats

## Hierarchy

- `Web3Provider`

  ↳ **`ArbitrumProvider`**

## Constructors

### constructor

• **new ArbitrumProvider**(`provider`, `network?`): [`ArbitrumProvider`](ArbitrumProvider.md)

Arbitrum specific formats

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `provider` | `JsonRpcProvider` | Must be connected to an Arbitrum network |
| `network?` | `Networkish` | Must be an Arbitrum network |

#### Returns

[`ArbitrumProvider`](ArbitrumProvider.md)

#### Overrides

Web3Provider.constructor

#### Defined in

[src/lib/utils/arbProvider.ts:77](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/utils/arbProvider.ts#L77)

## Properties

### \_bootstrapPoll

• **\_bootstrapPoll**: `Timer`

#### Inherited from

Web3Provider.\_bootstrapPoll

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:66

___

### \_emitted

• **\_emitted**: `Object`

#### Index signature

▪ [eventName: `string`]: `number` \| ``"pending"``

#### Inherited from

Web3Provider.\_emitted

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:61

___

### \_eventLoopCache

• **\_eventLoopCache**: `Record`\<`string`, `Promise`\<`any`\>\>

#### Inherited from

Web3Provider.\_eventLoopCache

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:32

___

### \_events

• **\_events**: `Event`[]

#### Inherited from

Web3Provider.\_events

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:59

___

### \_fastBlockNumber

• **\_fastBlockNumber**: `number`

#### Inherited from

Web3Provider.\_fastBlockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:69

___

### \_fastBlockNumberPromise

• **\_fastBlockNumberPromise**: `Promise`\<`number`\>

#### Inherited from

Web3Provider.\_fastBlockNumberPromise

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:70

___

### \_fastQueryDate

• **\_fastQueryDate**: `number`

#### Inherited from

Web3Provider.\_fastQueryDate

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:71

___

### \_internalBlockNumber

• **\_internalBlockNumber**: `Promise`\<\{ `blockNumber`: `number` ; `reqTime`: `number` ; `respTime`: `number`  }\>

#### Inherited from

Web3Provider.\_internalBlockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:73

___

### \_isProvider

• `Readonly` **\_isProvider**: `boolean`

#### Inherited from

Web3Provider.\_isProvider

#### Defined in

node_modules/@ethersproject/abstract-provider/lib/index.d.ts:152

___

### \_lastBlockNumber

• **\_lastBlockNumber**: `number`

#### Inherited from

Web3Provider.\_lastBlockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:67

___

### \_maxFilterBlockRange

• **\_maxFilterBlockRange**: `number`

#### Inherited from

Web3Provider.\_maxFilterBlockRange

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:68

___

### \_maxInternalBlockNumber

• **\_maxInternalBlockNumber**: `number`

#### Inherited from

Web3Provider.\_maxInternalBlockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:72

___

### \_network

• **\_network**: `Network`

#### Inherited from

Web3Provider.\_network

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:58

___

### \_networkPromise

• **\_networkPromise**: `Promise`\<`Network`\>

#### Inherited from

Web3Provider.\_networkPromise

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:57

___

### \_nextId

• **\_nextId**: `number`

#### Inherited from

Web3Provider.\_nextId

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:31

___

### \_pendingFilter

• **\_pendingFilter**: `Promise`\<`number`\>

#### Inherited from

Web3Provider.\_pendingFilter

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:30

___

### \_poller

• **\_poller**: `Timer`

#### Inherited from

Web3Provider.\_poller

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:65

___

### \_pollingInterval

• **\_pollingInterval**: `number`

#### Inherited from

Web3Provider.\_pollingInterval

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:64

___

### anyNetwork

• `Readonly` **anyNetwork**: `boolean`

#### Inherited from

Web3Provider.anyNetwork

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:78

___

### connection

• `Readonly` **connection**: `ConnectionInfo`

#### Inherited from

Web3Provider.connection

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:29

___

### disableCcipRead

• **disableCcipRead**: `boolean`

#### Inherited from

Web3Provider.disableCcipRead

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:79

___

### formatter

• **formatter**: `Formatter`

#### Inherited from

Web3Provider.formatter

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:60

___

### jsonRpcFetchFunc

• `Readonly` **jsonRpcFetchFunc**: `JsonRpcFetchFunc`

#### Inherited from

Web3Provider.jsonRpcFetchFunc

#### Defined in

node_modules/@ethersproject/providers/lib/web3-provider.d.ts:24

___

### provider

• `Readonly` **provider**: `ExternalProvider`

#### Inherited from

Web3Provider.provider

#### Defined in

node_modules/@ethersproject/providers/lib/web3-provider.d.ts:23

___

### arbFormatter

▪ `Static` `Private` **arbFormatter**: `ArbFormatter`

#### Defined in

[src/lib/utils/arbProvider.ts:70](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/utils/arbProvider.ts#L70)

## Accessors

### \_cache

• `get` **_cache**(): `Record`\<`string`, `Promise`\<`any`\>\>

#### Returns

`Record`\<`string`, `Promise`\<`any`\>\>

#### Inherited from

Web3Provider.\_cache

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:33

___

### blockNumber

• `get` **blockNumber**(): `number`

#### Returns

`number`

#### Inherited from

Web3Provider.blockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:101

___

### network

• `get` **network**(): `Network`

#### Returns

`Network`

#### Inherited from

Web3Provider.network

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:98

___

### polling

• `get` **polling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Web3Provider.polling

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:102

• `set` **polling**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`void`

#### Inherited from

Web3Provider.polling

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:103

___

### pollingInterval

• `get` **pollingInterval**(): `number`

#### Returns

`number`

#### Inherited from

Web3Provider.pollingInterval

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:104

• `set` **pollingInterval**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Inherited from

Web3Provider.pollingInterval

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:105

___

### ready

• `get` **ready**(): `Promise`\<`Network`\>

#### Returns

`Promise`\<`Network`\>

#### Inherited from

Web3Provider.ready

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:91

## Methods

### \_addEventListener

▸ **_addEventListener**(`eventName`, `listener`, `once`): `this`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `EventType` |
| `listener` | `Listener` |
| `once` | `boolean` |

#### Returns

`this`

#### Inherited from

Web3Provider.\_addEventListener

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:147

___

### \_call

▸ **_call**(`transaction`, `blockTag`, `attempt`): `Promise`\<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `TransactionRequest` |
| `blockTag` | `BlockTag` |
| `attempt` | `number` |

#### Returns

`Promise`\<`string`\>

#### Inherited from

Web3Provider.\_call

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:127

___

### \_getAddress

▸ **_getAddress**(`addressOrName`): `Promise`\<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`\<`string`\> |

#### Returns

`Promise`\<`string`\>

#### Inherited from

Web3Provider.\_getAddress

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:130

___

### \_getBlock

▸ **_getBlock**(`blockHashOrBlockTag`, `includeTransactions?`): `Promise`\<`Block` \| `BlockWithTransactions`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | `BlockTag` \| `Promise`\<`BlockTag`\> |
| `includeTransactions?` | `boolean` |

#### Returns

`Promise`\<`Block` \| `BlockWithTransactions`\>

#### Inherited from

Web3Provider.\_getBlock

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:131

___

### \_getBlockTag

▸ **_getBlockTag**(`blockTag`): `Promise`\<`BlockTag`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag` | `BlockTag` \| `Promise`\<`BlockTag`\> |

#### Returns

`Promise`\<`BlockTag`\>

#### Inherited from

Web3Provider.\_getBlockTag

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:138

___

### \_getFastBlockNumber

▸ **_getFastBlockNumber**(): `Promise`\<`number`\>

#### Returns

`Promise`\<`number`\>

#### Inherited from

Web3Provider.\_getFastBlockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:106

___

### \_getFilter

▸ **_getFilter**(`filter`): `Promise`\<`Filter` \| `FilterByBlockHash`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | `Filter` \| `FilterByBlockHash` \| `Promise`\<`Filter` \| `FilterByBlockHash`\> |

#### Returns

`Promise`\<`Filter` \| `FilterByBlockHash`\>

#### Inherited from

Web3Provider.\_getFilter

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:126

___

### \_getInternalBlockNumber

▸ **_getInternalBlockNumber**(`maxAge`): `Promise`\<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `maxAge` | `number` |

#### Returns

`Promise`\<`number`\>

#### Inherited from

Web3Provider.\_getInternalBlockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:95

___

### \_getResolver

▸ **_getResolver**(`name`, `operation?`): `Promise`\<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `operation?` | `string` |

#### Returns

`Promise`\<`string`\>

#### Inherited from

Web3Provider.\_getResolver

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:140

___

### \_getTransactionRequest

▸ **_getTransactionRequest**(`transaction`): `Promise`\<`Transaction`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `Deferrable`\<`TransactionRequest`\> |

#### Returns

`Promise`\<`Transaction`\>

#### Inherited from

Web3Provider.\_getTransactionRequest

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:125

___

### \_ready

▸ **_ready**(): `Promise`\<`Network`\>

#### Returns

`Promise`\<`Network`\>

#### Inherited from

Web3Provider.\_ready

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:90

___

### \_setFastBlockNumber

▸ **_setFastBlockNumber**(`blockNumber`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockNumber` | `number` |

#### Returns

`void`

#### Inherited from

Web3Provider.\_setFastBlockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:107

___

### \_startEvent

▸ **_startEvent**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `Event` |

#### Returns

`void`

#### Inherited from

Web3Provider.\_startEvent

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:44

___

### \_startPending

▸ **_startPending**(): `void`

#### Returns

`void`

#### Inherited from

Web3Provider.\_startPending

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:45

___

### \_stopEvent

▸ **_stopEvent**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `Event` |

#### Returns

`void`

#### Inherited from

Web3Provider.\_stopEvent

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:46

___

### \_uncachedDetectNetwork

▸ **_uncachedDetectNetwork**(): `Promise`\<`Network`\>

#### Returns

`Promise`\<`Network`\>

#### Inherited from

Web3Provider.\_uncachedDetectNetwork

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:37

___

### \_waitForTransaction

▸ **_waitForTransaction**(`transactionHash`, `confirmations`, `timeout`, `replaceable`): `Promise`\<`TransactionReceipt`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` |
| `confirmations` | `number` |
| `timeout` | `number` |
| `replaceable` | `Object` |
| `replaceable.data` | `string` |
| `replaceable.from` | `string` |
| `replaceable.nonce` | `number` |
| `replaceable.startBlock` | `number` |
| `replaceable.to` | `string` |
| `replaceable.value` | `BigNumber` |

#### Returns

`Promise`\<`TransactionReceipt`\>

#### Inherited from

Web3Provider.\_waitForTransaction

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:109

___

### \_wrapTransaction

▸ **_wrapTransaction**(`tx`, `hash?`, `startBlock?`): `TransactionResponse`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | `Transaction` |
| `hash?` | `string` |
| `startBlock?` | `number` |

#### Returns

`TransactionResponse`

#### Inherited from

Web3Provider.\_wrapTransaction

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:123

___

### addListener

▸ **addListener**(`eventName`, `listener`): `Provider`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `EventType` |
| `listener` | `Listener` |

#### Returns

`Provider`

#### Inherited from

Web3Provider.addListener

#### Defined in

node_modules/@ethersproject/abstract-provider/lib/index.d.ts:149

___

### call

▸ **call**(`transaction`, `blockTag?`): `Promise`\<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `Deferrable`\<`TransactionRequest`\> |
| `blockTag?` | `BlockTag` \| `Promise`\<`BlockTag`\> |

#### Returns

`Promise`\<`string`\>

#### Inherited from

Web3Provider.call

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:128

___

### ccipReadFetch

▸ **ccipReadFetch**(`tx`, `calldata`, `urls`): `Promise`\<``null`` \| `string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | `Transaction` |
| `calldata` | `string` |
| `urls` | `string`[] |

#### Returns

`Promise`\<``null`` \| `string`\>

#### Inherited from

Web3Provider.ccipReadFetch

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:94

___

### detectNetwork

▸ **detectNetwork**(): `Promise`\<`Network`\>

#### Returns

`Promise`\<`Network`\>

#### Inherited from

Web3Provider.detectNetwork

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:36

___

### emit

▸ **emit**(`eventName`, `...args`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `EventType` |
| `...args` | `any`[] |

#### Returns

`boolean`

#### Inherited from

Web3Provider.emit

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:150

___

### estimateGas

▸ **estimateGas**(`transaction`): `Promise`\<`BigNumber`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `Deferrable`\<`TransactionRequest`\> |

#### Returns

`Promise`\<`BigNumber`\>

#### Inherited from

Web3Provider.estimateGas

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:129

___

### getAvatar

▸ **getAvatar**(`nameOrAddress`): `Promise`\<``null`` \| `string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `nameOrAddress` | `string` |

#### Returns

`Promise`\<``null`` \| `string`\>

#### Inherited from

Web3Provider.getAvatar

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:143

___

### getBalance

▸ **getBalance**(`addressOrName`, `blockTag?`): `Promise`\<`BigNumber`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`\<`string`\> |
| `blockTag?` | `BlockTag` \| `Promise`\<`BlockTag`\> |

#### Returns

`Promise`\<`BigNumber`\>

#### Inherited from

Web3Provider.getBalance

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:119

___

### getBlock

▸ **getBlock**(`blockHashOrBlockTag`): `Promise`\<`ArbBlock`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | `BlockTag` \| `Promise`\<`BlockTag`\> |

#### Returns

`Promise`\<`ArbBlock`\>

#### Overrides

Web3Provider.getBlock

#### Defined in

[src/lib/utils/arbProvider.ts:101](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/utils/arbProvider.ts#L101)

___

### getBlockNumber

▸ **getBlockNumber**(): `Promise`\<`number`\>

#### Returns

`Promise`\<`number`\>

#### Inherited from

Web3Provider.getBlockNumber

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:117

___

### getBlockWithTransactions

▸ **getBlockWithTransactions**(`blockHashOrBlockTag`): `Promise`\<`ArbBlockWithTransactions`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | `BlockTag` \| `Promise`\<`BlockTag`\> |

#### Returns

`Promise`\<`ArbBlockWithTransactions`\>

#### Overrides

Web3Provider.getBlockWithTransactions

#### Defined in

[src/lib/utils/arbProvider.ts:93](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/utils/arbProvider.ts#L93)

___

### getCode

▸ **getCode**(`addressOrName`, `blockTag?`): `Promise`\<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`\<`string`\> |
| `blockTag?` | `BlockTag` \| `Promise`\<`BlockTag`\> |

#### Returns

`Promise`\<`string`\>

#### Inherited from

Web3Provider.getCode

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:121

___

### getEtherPrice

▸ **getEtherPrice**(): `Promise`\<`number`\>

#### Returns

`Promise`\<`number`\>

#### Inherited from

Web3Provider.getEtherPrice

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:137

___

### getFeeData

▸ **getFeeData**(): `Promise`\<`FeeData`\>

#### Returns

`Promise`\<`FeeData`\>

#### Inherited from

Web3Provider.getFeeData

#### Defined in

node_modules/@ethersproject/abstract-provider/lib/index.d.ts:127

___

### getGasPrice

▸ **getGasPrice**(): `Promise`\<`BigNumber`\>

#### Returns

`Promise`\<`BigNumber`\>

#### Inherited from

Web3Provider.getGasPrice

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:118

___

### getLogs

▸ **getLogs**(`filter`): `Promise`\<`Log`[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | `Filter` \| `FilterByBlockHash` \| `Promise`\<`Filter` \| `FilterByBlockHash`\> |

#### Returns

`Promise`\<`Log`[]\>

#### Inherited from

Web3Provider.getLogs

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:136

___

### getNetwork

▸ **getNetwork**(): `Promise`\<`Network`\>

#### Returns

`Promise`\<`Network`\>

#### Inherited from

Web3Provider.getNetwork

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:100

___

### getResolver

▸ **getResolver**(`name`): `Promise`\<``null`` \| `Resolver`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`\<``null`` \| `Resolver`\>

#### Inherited from

Web3Provider.getResolver

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:139

___

### getSigner

▸ **getSigner**(`addressOrIndex?`): `JsonRpcSigner`

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrIndex?` | `string` \| `number` |

#### Returns

`JsonRpcSigner`

#### Inherited from

Web3Provider.getSigner

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:38

___

### getStorageAt

▸ **getStorageAt**(`addressOrName`, `position`, `blockTag?`): `Promise`\<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`\<`string`\> |
| `position` | `BigNumberish` \| `Promise`\<`BigNumberish`\> |
| `blockTag?` | `BlockTag` \| `Promise`\<`BlockTag`\> |

#### Returns

`Promise`\<`string`\>

#### Inherited from

Web3Provider.getStorageAt

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:122

___

### getTransaction

▸ **getTransaction**(`transactionHash`): `Promise`\<`TransactionResponse`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` \| `Promise`\<`string`\> |

#### Returns

`Promise`\<`TransactionResponse`\>

#### Inherited from

Web3Provider.getTransaction

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:134

___

### getTransactionCount

▸ **getTransactionCount**(`addressOrName`, `blockTag?`): `Promise`\<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`\<`string`\> |
| `blockTag?` | `BlockTag` \| `Promise`\<`BlockTag`\> |

#### Returns

`Promise`\<`number`\>

#### Inherited from

Web3Provider.getTransactionCount

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:120

___

### getTransactionReceipt

▸ **getTransactionReceipt**(`transactionHash`): `Promise`\<`ArbTransactionReceipt`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` \| `Promise`\<`string`\> |

#### Returns

`Promise`\<`ArbTransactionReceipt`\>

#### Overrides

Web3Provider.getTransactionReceipt

#### Defined in

[src/lib/utils/arbProvider.ts:85](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/utils/arbProvider.ts#L85)

___

### getUncheckedSigner

▸ **getUncheckedSigner**(`addressOrIndex?`): `UncheckedJsonRpcSigner`

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrIndex?` | `string` \| `number` |

#### Returns

`UncheckedJsonRpcSigner`

#### Inherited from

Web3Provider.getUncheckedSigner

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:39

___

### listAccounts

▸ **listAccounts**(): `Promise`\<`string`[]\>

#### Returns

`Promise`\<`string`[]\>

#### Inherited from

Web3Provider.listAccounts

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:40

___

### listenerCount

▸ **listenerCount**(`eventName?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | `EventType` |

#### Returns

`number`

#### Inherited from

Web3Provider.listenerCount

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:151

___

### listeners

▸ **listeners**(`eventName?`): `Listener`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | `EventType` |

#### Returns

`Listener`[]

#### Inherited from

Web3Provider.listeners

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:152

___

### lookupAddress

▸ **lookupAddress**(`address`): `Promise`\<``null`` \| `string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` \| `Promise`\<`string`\> |

#### Returns

`Promise`\<``null`` \| `string`\>

#### Inherited from

Web3Provider.lookupAddress

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:142

___

### off

▸ **off**(`eventName`, `listener?`): `this`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `EventType` |
| `listener?` | `Listener` |

#### Returns

`this`

#### Inherited from

Web3Provider.off

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:153

___

### on

▸ **on**(`eventName`, `listener`): `this`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `EventType` |
| `listener` | `Listener` |

#### Returns

`this`

#### Inherited from

Web3Provider.on

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:148

___

### once

▸ **once**(`eventName`, `listener`): `this`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `EventType` |
| `listener` | `Listener` |

#### Returns

`this`

#### Inherited from

Web3Provider.once

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:149

___

### perform

▸ **perform**(`method`, `params`): `Promise`\<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `params` | `any` |

#### Returns

`Promise`\<`any`\>

#### Inherited from

Web3Provider.perform

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:43

___

### poll

▸ **poll**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Inherited from

Web3Provider.poll

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:96

___

### prepareRequest

▸ **prepareRequest**(`method`, `params`): [`string`, `any`[]]

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `params` | `any` |

#### Returns

[`string`, `any`[]]

#### Inherited from

Web3Provider.prepareRequest

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:42

___

### removeAllListeners

▸ **removeAllListeners**(`eventName?`): `this`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | `EventType` |

#### Returns

`this`

#### Inherited from

Web3Provider.removeAllListeners

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:154

___

### removeListener

▸ **removeListener**(`eventName`, `listener`): `Provider`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `EventType` |
| `listener` | `Listener` |

#### Returns

`Provider`

#### Inherited from

Web3Provider.removeListener

#### Defined in

node_modules/@ethersproject/abstract-provider/lib/index.d.ts:150

___

### resetEventsBlock

▸ **resetEventsBlock**(`blockNumber`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockNumber` | `number` |

#### Returns

`void`

#### Inherited from

Web3Provider.resetEventsBlock

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:97

___

### resolveName

▸ **resolveName**(`name`): `Promise`\<``null`` \| `string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` \| `Promise`\<`string`\> |

#### Returns

`Promise`\<``null`` \| `string`\>

#### Inherited from

Web3Provider.resolveName

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:141

___

### send

▸ **send**(`method`, `params`): `Promise`\<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `params` | `any`[] |

#### Returns

`Promise`\<`any`\>

#### Inherited from

Web3Provider.send

#### Defined in

node_modules/@ethersproject/providers/lib/web3-provider.d.ts:26

___

### sendTransaction

▸ **sendTransaction**(`signedTransaction`): `Promise`\<`TransactionResponse`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `signedTransaction` | `string` \| `Promise`\<`string`\> |

#### Returns

`Promise`\<`TransactionResponse`\>

#### Inherited from

Web3Provider.sendTransaction

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:124

___

### waitForTransaction

▸ **waitForTransaction**(`transactionHash`, `confirmations?`, `timeout?`): `Promise`\<`TransactionReceipt`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` |
| `confirmations?` | `number` |
| `timeout?` | `number` |

#### Returns

`Promise`\<`TransactionReceipt`\>

#### Inherited from

Web3Provider.waitForTransaction

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:108

___

### defaultUrl

▸ **defaultUrl**(): `string`

#### Returns

`string`

#### Inherited from

Web3Provider.defaultUrl

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:35

___

### getFormatter

▸ **getFormatter**(): `Formatter`

#### Returns

`Formatter`

#### Overrides

Web3Provider.getFormatter

#### Defined in

[src/lib/utils/arbProvider.ts:81](https://github.com/OffchainLabs/arbitrum-sdk/blob/4d1c5a4e2/src/lib/utils/arbProvider.ts#L81)

___

### getNetwork

▸ **getNetwork**(`network`): `Network`

#### Parameters

| Name | Type |
| :------ | :------ |
| `network` | `Networkish` |

#### Returns

`Network`

#### Inherited from

Web3Provider.getNetwork

#### Defined in

node_modules/@ethersproject/providers/lib/base-provider.d.ts:93

___

### hexlifyTransaction

▸ **hexlifyTransaction**(`transaction`, `allowExtra?`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `TransactionRequest` |
| `allowExtra?` | `Object` |

#### Returns

`Object`

#### Inherited from

Web3Provider.hexlifyTransaction

#### Defined in

node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:47

___

### isProvider

▸ **isProvider**(`value`): value is Provider

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

value is Provider

#### Inherited from

Web3Provider.isProvider

#### Defined in

node_modules/@ethersproject/abstract-provider/lib/index.d.ts:154
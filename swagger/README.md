# Documentation for Ord Node API

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://api/v1*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *BRC20Api* | [**brc20AddressAddressBalanceGet**](Apis/BRC20Api.md#brc20addressaddressbalanceget) | **GET** /brc20/address/{address}/balance | Get brc20 balance by btc address |
*BRC20Api* | [**brc20AddressAddressTransferableGet**](Apis/BRC20Api.md#brc20addressaddresstransferableget) | **GET** /brc20/address/{address}/transferable | Get brc20 transferable by btc address |
*BRC20Api* | [**brc20BlockBlockHashEventsGet**](Apis/BRC20Api.md#brc20blockblockhasheventsget) | **GET** /brc20/block/{blockHash}/events | Get brc20 block by blockHash |
*BRC20Api* | [**brc20TickGet**](Apis/BRC20Api.md#brc20tickget) | **GET** /brc20/tick | Get brc20 tick list |
*BRC20Api* | [**brc20TickTickAddressAddressBalanceGet**](Apis/BRC20Api.md#brc20ticktickaddressaddressbalanceget) | **GET** /brc20/tick/{tick}/address/{address}/balance | Get brc20 balance by tick and address |
*BRC20Api* | [**brc20TickTickAddressAddressTransferableGet**](Apis/BRC20Api.md#brc20ticktickaddressaddresstransferableget) | **GET** /brc20/tick/{tick}/address/{address}/transferable | Get brc20 transferable by tick and address |
*BRC20Api* | [**brc20TickTickGet**](Apis/BRC20Api.md#brc20ticktickget) | **GET** /brc20/tick/{tick} | Get brc20 tick by name |
*BRC20Api* | [**brc20TxTxidEventsGet**](Apis/BRC20Api.md#brc20txtxideventsget) | **GET** /brc20/tx/{txid}/events | Get brc20 tx events by txid |
*BRC20Api* | [**brc20TxTxidGet**](Apis/BRC20Api.md#brc20txtxidget) | **GET** /brc20/tx/{txid} | Get brc20 tx by txid |
| *NodeStatusApi* | [**nodeInfoGet**](Apis/NodeStatusApi.md#nodeinfoget) | **GET** /node/info | Get ord and bitcoin node status |
| *OrdApi* | [**ordIdInscriptionIdInscriptionGet**](Apis/OrdApi.md#ordidinscriptionidinscriptionget) | **GET** /ord/id/{inscriptionId}/inscription | Get ord inscription by inscriptionId |
*OrdApi* | [**ordNumberInscriptionNumberInscriptionGet**](Apis/OrdApi.md#ordnumberinscriptionnumberinscriptionget) | **GET** /ord/number/{inscriptionNumber}/inscription | Get ord inscription by inscriptionNumber |
*OrdApi* | [**ordOutpointOutpointInfoGet**](Apis/OrdApi.md#ordoutpointoutpointinfoget) | **GET** /ord/outpoint/{outpoint}/info | Get ord output info by outpoint |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [Address](./Models/Address.md)
 - [AllBRC20Balance](./Models/AllBRC20Balance.md)
 - [AllBRC20Tick](./Models/AllBRC20Tick.md)
 - [ApiError400](./Models/ApiError400.md)
 - [ApiError404](./Models/ApiError404.md)
 - [ApiError500](./Models/ApiError500.md)
 - [ApiResponse](./Models/ApiResponse.md)
 - [BRC20Balance](./Models/BRC20Balance.md)
 - [BRC20BlockEvents](./Models/BRC20BlockEvents.md)
 - [BRC20DeployEvent](./Models/BRC20DeployEvent.md)
 - [BRC20DeployEvent_allOf](./Models/BRC20DeployEvent_allOf.md)
 - [BRC20DeployOperation](./Models/BRC20DeployOperation.md)
 - [BRC20InscribeTransferEvent](./Models/BRC20InscribeTransferEvent.md)
 - [BRC20InscribeTransferEvent_allOf](./Models/BRC20InscribeTransferEvent_allOf.md)
 - [BRC20InscriptionMessage](./Models/BRC20InscriptionMessage.md)
 - [BRC20MintEvent](./Models/BRC20MintEvent.md)
 - [BRC20MintEvent_allOf](./Models/BRC20MintEvent_allOf.md)
 - [BRC20MintOperation](./Models/BRC20MintOperation.md)
 - [BRC20Operation](./Models/BRC20Operation.md)
 - [BRC20Tick](./Models/BRC20Tick.md)
 - [BRC20TransferEvent](./Models/BRC20TransferEvent.md)
 - [BRC20TransferEvent_allOf](./Models/BRC20TransferEvent_allOf.md)
 - [BRC20TransferOperation](./Models/BRC20TransferOperation.md)
 - [BRC20TransferableInscription](./Models/BRC20TransferableInscription.md)
 - [BRC20TransferableInscriptions](./Models/BRC20TransferableInscriptions.md)
 - [BRC20TxEvent](./Models/BRC20TxEvent.md)
 - [BRC20TxEvents](./Models/BRC20TxEvents.md)
 - [Brc20Transaction](./Models/Brc20Transaction.md)
 - [HeightInfo](./Models/HeightInfo.md)
 - [Inscription](./Models/Inscription.md)
 - [InscriptionDigest](./Models/InscriptionDigest.md)
 - [NonStandard](./Models/NonStandard.md)
 - [OutpointInfo](./Models/OutpointInfo.md)
 - [ScriptPubKey](./Models/ScriptPubKey.md)
 - [_brc20_address__address__balance_get_200_response](./Models/_brc20_address__address__balance_get_200_response.md)
 - [_brc20_address__address__balance_get_200_response_allOf](./Models/_brc20_address__address__balance_get_200_response_allOf.md)
 - [_brc20_block__blockHash__events_get_200_response](./Models/_brc20_block__blockHash__events_get_200_response.md)
 - [_brc20_block__blockHash__events_get_200_response_allOf](./Models/_brc20_block__blockHash__events_get_200_response_allOf.md)
 - [_brc20_tick__tick__address__address__balance_get_200_response](./Models/_brc20_tick__tick__address__address__balance_get_200_response.md)
 - [_brc20_tick__tick__address__address__balance_get_200_response_allOf](./Models/_brc20_tick__tick__address__address__balance_get_200_response_allOf.md)
 - [_brc20_tick__tick__address__address__transferable_get_200_response](./Models/_brc20_tick__tick__address__address__transferable_get_200_response.md)
 - [_brc20_tick__tick__address__address__transferable_get_200_response_allOf](./Models/_brc20_tick__tick__address__address__transferable_get_200_response_allOf.md)
 - [_brc20_tick__tick__get_200_response](./Models/_brc20_tick__tick__get_200_response.md)
 - [_brc20_tick__tick__get_200_response_allOf](./Models/_brc20_tick__tick__get_200_response_allOf.md)
 - [_brc20_tick_get_200_response](./Models/_brc20_tick_get_200_response.md)
 - [_brc20_tick_get_200_response_allOf](./Models/_brc20_tick_get_200_response_allOf.md)
 - [_brc20_tx__txid__events_get_200_response](./Models/_brc20_tx__txid__events_get_200_response.md)
 - [_brc20_tx__txid__events_get_200_response_allOf](./Models/_brc20_tx__txid__events_get_200_response_allOf.md)
 - [_brc20_tx__txid__get_200_response](./Models/_brc20_tx__txid__get_200_response.md)
 - [_brc20_tx__txid__get_200_response_allOf](./Models/_brc20_tx__txid__get_200_response_allOf.md)
 - [_node_info_get_200_response](./Models/_node_info_get_200_response.md)
 - [_node_info_get_200_response_allOf](./Models/_node_info_get_200_response_allOf.md)
 - [_ord_id__inscriptionId__inscription_get_200_response](./Models/_ord_id__inscriptionId__inscription_get_200_response.md)
 - [_ord_id__inscriptionId__inscription_get_200_response_allOf](./Models/_ord_id__inscriptionId__inscription_get_200_response_allOf.md)
 - [_ord_outpoint__outpoint__info_get_200_response](./Models/_ord_outpoint__outpoint__info_get_200_response.md)
 - [_ord_outpoint__outpoint__info_get_200_response_allOf](./Models/_ord_outpoint__outpoint__info_get_200_response_allOf.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

All endpoints do not require authorization.

# BRC20Api

All URIs are relative to *http://api/v1*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**brc20AddressAddressBalanceGet**](BRC20Api.md#brc20AddressAddressBalanceGet) | **GET** /brc20/address/{address}/balance | Get brc20 balance by btc address |
| [**brc20AddressAddressTransferableGet**](BRC20Api.md#brc20AddressAddressTransferableGet) | **GET** /brc20/address/{address}/transferable | Get brc20 transferable by btc address |
| [**brc20BlockBlockHashEventsGet**](BRC20Api.md#brc20BlockBlockHashEventsGet) | **GET** /brc20/block/{blockHash}/events | Get brc20 block by blockHash |
| [**brc20TickGet**](BRC20Api.md#brc20TickGet) | **GET** /brc20/tick | Get brc20 tick list |
| [**brc20TickTickAddressAddressBalanceGet**](BRC20Api.md#brc20TickTickAddressAddressBalanceGet) | **GET** /brc20/tick/{tick}/address/{address}/balance | Get brc20 balance by tick and address |
| [**brc20TickTickAddressAddressTransferableGet**](BRC20Api.md#brc20TickTickAddressAddressTransferableGet) | **GET** /brc20/tick/{tick}/address/{address}/transferable | Get brc20 transferable by tick and address |
| [**brc20TickTickGet**](BRC20Api.md#brc20TickTickGet) | **GET** /brc20/tick/{tick} | Get brc20 tick by name |
| [**brc20TxTxidEventsGet**](BRC20Api.md#brc20TxTxidEventsGet) | **GET** /brc20/tx/{txid}/events | Get brc20 tx events by txid |
| [**brc20TxTxidGet**](BRC20Api.md#brc20TxTxidGet) | **GET** /brc20/tx/{txid} | Get brc20 tx by txid |


<a name="brc20AddressAddressBalanceGet"></a>
# **brc20AddressAddressBalanceGet**
> _brc20_address__address__balance_get_200_response brc20AddressAddressBalanceGet(address)

Get brc20 balance by btc address

    Returns a json object with the brc20 balance info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **address** | **String**| The btc address. | [default to null] |

### Return type

[**_brc20_address__address__balance_get_200_response**](../Models/_brc20_address__address__balance_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="brc20AddressAddressTransferableGet"></a>
# **brc20AddressAddressTransferableGet**
> _brc20_tick__tick__address__address__transferable_get_200_response brc20AddressAddressTransferableGet(address)

Get brc20 transferable by btc address

    Returns a json object with the brc20 transferable info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **address** | **String**| The btc address. | [default to null] |

### Return type

[**_brc20_tick__tick__address__address__transferable_get_200_response**](../Models/_brc20_tick__tick__address__address__transferable_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="brc20BlockBlockHashEventsGet"></a>
# **brc20BlockBlockHashEventsGet**
> _brc20_block__blockHash__events_get_200_response brc20BlockBlockHashEventsGet(blockHash)

Get brc20 block by blockHash

    Returns a json object with the brc20 block info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **blockHash** | **String**| The blockHash. | [default to null] |

### Return type

[**_brc20_block__blockHash__events_get_200_response**](../Models/_brc20_block__blockHash__events_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="brc20TickGet"></a>
# **brc20TickGet**
> _brc20_tick_get_200_response brc20TickGet()

Get brc20 tick list

    Returns a json object with the brc20 tick list.

### Parameters
This endpoint does not need any parameter.

### Return type

[**_brc20_tick_get_200_response**](../Models/_brc20_tick_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="brc20TickTickAddressAddressBalanceGet"></a>
# **brc20TickTickAddressAddressBalanceGet**
> _brc20_tick__tick__address__address__balance_get_200_response brc20TickTickAddressAddressBalanceGet(tick, address)

Get brc20 balance by tick and address

    Returns a json object with the brc20 balance info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **tick** | **String**| The brc20 tick name. | [default to null] |
| **address** | **String**| The address. | [default to null] |

### Return type

[**_brc20_tick__tick__address__address__balance_get_200_response**](../Models/_brc20_tick__tick__address__address__balance_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="brc20TickTickAddressAddressTransferableGet"></a>
# **brc20TickTickAddressAddressTransferableGet**
> _brc20_tick__tick__address__address__transferable_get_200_response brc20TickTickAddressAddressTransferableGet(tick, address)

Get brc20 transferable by tick and address

    Returns a json object with the brc20 transferable info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **tick** | **String**| The brc20 tick name. | [default to null] |
| **address** | **String**| The btc address. | [default to null] |

### Return type

[**_brc20_tick__tick__address__address__transferable_get_200_response**](../Models/_brc20_tick__tick__address__address__transferable_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="brc20TickTickGet"></a>
# **brc20TickTickGet**
> _brc20_tick__tick__get_200_response brc20TickTickGet(tick)

Get brc20 tick by name

    Returns a json object with the brc20 tick info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **tick** | **String**| The 4 bytes brc20 tick name. | [default to null] |

### Return type

[**_brc20_tick__tick__get_200_response**](../Models/_brc20_tick__tick__get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="brc20TxTxidEventsGet"></a>
# **brc20TxTxidEventsGet**
> _brc20_tx__txid__events_get_200_response brc20TxTxidEventsGet(txid)

Get brc20 tx events by txid

    Returns a json object with the brc20 tx info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **txid** | **String**| The txid. | [default to null] |

### Return type

[**_brc20_tx__txid__events_get_200_response**](../Models/_brc20_tx__txid__events_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="brc20TxTxidGet"></a>
# **brc20TxTxidGet**
> _brc20_tx__txid__get_200_response brc20TxTxidGet(txid)

Get brc20 tx by txid

    Returns a json object with the brc20 tx info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **txid** | **String**| The txid. | [default to null] |

### Return type

[**_brc20_tx__txid__get_200_response**](../Models/_brc20_tx__txid__get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


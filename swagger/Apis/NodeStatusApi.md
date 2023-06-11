# NodeStatusApi

All URIs are relative to *http://api/v1*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**nodeInfoGet**](NodeStatusApi.md#nodeInfoGet) | **GET** /node/info | Get ord and bitcoin node status |


<a name="nodeInfoGet"></a>
# **nodeInfoGet**
> _node_info_get_200_response nodeInfoGet(btc)

Get ord and bitcoin node status

    Returns a json object with the bitcoin network status.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **btc** | **Boolean**| If true, returns the bitcoin network information. | [optional] [default to null] |

### Return type

[**_node_info_get_200_response**](../Models/_node_info_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


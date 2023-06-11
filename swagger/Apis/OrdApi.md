# OrdApi

All URIs are relative to *http://api/v1*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**ordIdInscriptionIdInscriptionGet**](OrdApi.md#ordIdInscriptionIdInscriptionGet) | **GET** /ord/id/{inscriptionId}/inscription | Get ord inscription by inscriptionId |
| [**ordNumberInscriptionNumberInscriptionGet**](OrdApi.md#ordNumberInscriptionNumberInscriptionGet) | **GET** /ord/number/{inscriptionNumber}/inscription | Get ord inscription by inscriptionNumber |
| [**ordOutpointOutpointInfoGet**](OrdApi.md#ordOutpointOutpointInfoGet) | **GET** /ord/outpoint/{outpoint}/info | Get ord output info by outpoint |


<a name="ordIdInscriptionIdInscriptionGet"></a>
# **ordIdInscriptionIdInscriptionGet**
> _ord_id__inscriptionId__inscription_get_200_response ordIdInscriptionIdInscriptionGet(inscriptionId)

Get ord inscription by inscriptionId

    Returns a json object with the ord inscription info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **inscriptionId** | **String**| The inscriptionId. | [default to null] |

### Return type

[**_ord_id__inscriptionId__inscription_get_200_response**](../Models/_ord_id__inscriptionId__inscription_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="ordNumberInscriptionNumberInscriptionGet"></a>
# **ordNumberInscriptionNumberInscriptionGet**
> _ord_id__inscriptionId__inscription_get_200_response ordNumberInscriptionNumberInscriptionGet(inscriptionNumber)

Get ord inscription by inscriptionNumber

    Returns a json object with the ord inscription info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **inscriptionNumber** | **Integer**| The inscriptionNumber. | [default to null] |

### Return type

[**_ord_id__inscriptionId__inscription_get_200_response**](../Models/_ord_id__inscriptionId__inscription_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="ordOutpointOutpointInfoGet"></a>
# **ordOutpointOutpointInfoGet**
> _ord_outpoint__outpoint__info_get_200_response ordOutpointOutpointInfoGet(outpoint)

Get ord output info by outpoint

    Returns a json object with the ord outpoint info.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **outpoint** | **String**| The outpoint. | [default to null] |

### Return type

[**_ord_outpoint__outpoint__info_get_200_response**](../Models/_ord_outpoint__outpoint__info_get_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


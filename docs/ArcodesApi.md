# openapi_client.ArcodesApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_arcodes_post**](ArcodesApi.md#orgs_v1_arcodes_post) | **POST** /{orgs}/v1/arcodes | Charge codes


# **orgs_v1_arcodes_post**
> OrgsV1ArcodesPost200Response orgs_v1_arcodes_post(orgs, get_ar_codes)

Charge codes

Returns all AR codes for a specified management company.

### Example


```python
import openapi_client
from openapi_client.models.get_ar_codes import GetArCodes
from openapi_client.models.orgs_v1_arcodes_post200_response import OrgsV1ArcodesPost200Response
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://apis.entrata.com/ext/orgs
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://apis.entrata.com/ext/orgs"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.ArcodesApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    get_ar_codes = openapi_client.GetArCodes() # GetArCodes | Returns all AR codes for a specified management company.

    try:
        # Charge codes
        api_response = api_instance.orgs_v1_arcodes_post(orgs, get_ar_codes)
        print("The response of ArcodesApi->orgs_v1_arcodes_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ArcodesApi->orgs_v1_arcodes_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **get_ar_codes** | [**GetArCodes**](GetArCodes.md)| Returns all AR codes for a specified management company. | 

### Return type

[**OrgsV1ArcodesPost200Response**](OrgsV1ArcodesPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Success |  -  |
**400** | Failure |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


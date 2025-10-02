# openapi_client.StatusApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_status_post**](StatusApi.md#orgs_v1_status_post) | **POST** /{orgs}/v1/status | API Health check


# **orgs_v1_status_post**
> OrgsV1StatusPost200Response orgs_v1_status_post(orgs, get_status)

API Health check

### Example


```python
import openapi_client
from openapi_client.models.get_status import GetStatus
from openapi_client.models.orgs_v1_status_post200_response import OrgsV1StatusPost200Response
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
    api_instance = openapi_client.StatusApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    get_status = openapi_client.GetStatus() # GetStatus | This API will specify the API health status whether it is running or not.

    try:
        # API Health check
        api_response = api_instance.orgs_v1_status_post(orgs, get_status)
        print("The response of StatusApi->orgs_v1_status_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling StatusApi->orgs_v1_status_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **get_status** | [**GetStatus**](GetStatus.md)| This API will specify the API health status whether it is running or not. | 

### Return type

[**OrgsV1StatusPost200Response**](OrgsV1StatusPost200Response.md)

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


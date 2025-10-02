# openapi_client.AppinfoApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_appinfo_post**](AppinfoApi.md#orgs_v1_appinfo_post) | **POST** /{orgs}/v1/appinfo | App info related APIs


# **orgs_v1_appinfo_post**
> OrgsV1AppinfoPost200Response orgs_v1_appinfo_post(orgs, orgs_v1_appinfo_post_request_inner)

App info related APIs

Please use `rsync` as the orgs value when calling the getAccessibleClients API.

### Example


```python
import openapi_client
from openapi_client.models.orgs_v1_appinfo_post200_response import OrgsV1AppinfoPost200Response
from openapi_client.models.orgs_v1_appinfo_post_request_inner import OrgsV1AppinfoPostRequestInner
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
    api_instance = openapi_client.AppinfoApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_appinfo_post_request_inner = [openapi_client.OrgsV1AppinfoPostRequestInner()] # List[OrgsV1AppinfoPostRequestInner] | 

    try:
        # App info related APIs
        api_response = api_instance.orgs_v1_appinfo_post(orgs, orgs_v1_appinfo_post_request_inner)
        print("The response of AppinfoApi->orgs_v1_appinfo_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AppinfoApi->orgs_v1_appinfo_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_appinfo_post_request_inner** | [**List[OrgsV1AppinfoPostRequestInner]**](OrgsV1AppinfoPostRequestInner.md)|  | 

### Return type

[**OrgsV1AppinfoPost200Response**](OrgsV1AppinfoPost200Response.md)

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


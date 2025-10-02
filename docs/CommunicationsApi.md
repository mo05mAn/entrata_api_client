# openapi_client.CommunicationsApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_communications_post**](CommunicationsApi.md#orgs_v1_communications_post) | **POST** /{orgs}/v1/communications | Communications


# **orgs_v1_communications_post**
> OrgsV1CommunicationsPost200Response orgs_v1_communications_post(orgs, orgs_v1_communications_post_request_inner)

Communications

### Example


```python
import openapi_client
from openapi_client.models.orgs_v1_communications_post200_response import OrgsV1CommunicationsPost200Response
from openapi_client.models.orgs_v1_communications_post_request_inner import OrgsV1CommunicationsPostRequestInner
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
    api_instance = openapi_client.CommunicationsApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_communications_post_request_inner = [openapi_client.OrgsV1CommunicationsPostRequestInner()] # List[OrgsV1CommunicationsPostRequestInner] | arPayment related APIs

    try:
        # Communications
        api_response = api_instance.orgs_v1_communications_post(orgs, orgs_v1_communications_post_request_inner)
        print("The response of CommunicationsApi->orgs_v1_communications_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunicationsApi->orgs_v1_communications_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_communications_post_request_inner** | [**List[OrgsV1CommunicationsPostRequestInner]**](OrgsV1CommunicationsPostRequestInner.md)| arPayment related APIs | 

### Return type

[**OrgsV1CommunicationsPost200Response**](OrgsV1CommunicationsPost200Response.md)

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


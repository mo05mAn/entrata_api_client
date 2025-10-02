# entrata_api_client.ApplicationsApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_applications_post**](ApplicationsApi.md#orgs_v1_applications_post) | **POST** /{orgs}/v1/applications | Applications


# **orgs_v1_applications_post**
> OrgsV1ApplicationsPost200Response orgs_v1_applications_post(orgs, orgs_v1_applications_post_request_inner)

Applications

### Example


```python
import entrata_api_client
from entrata_api_client.models.orgs_v1_applications_post200_response import OrgsV1ApplicationsPost200Response
from entrata_api_client.models.orgs_v1_applications_post_request_inner import OrgsV1ApplicationsPostRequestInner
from entrata_api_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://apis.entrata.com/ext/orgs
# See configuration.py for a list of all supported configuration parameters.
configuration = entrata_api_client.Configuration(
    host = "https://apis.entrata.com/ext/orgs"
)


# Enter a context with an instance of the API client
with entrata_api_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = entrata_api_client.ApplicationsApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_applications_post_request_inner = [entrata_api_client.OrgsV1ApplicationsPostRequestInner()] # List[OrgsV1ApplicationsPostRequestInner] | Application related APIs

    try:
        # Applications
        api_response = api_instance.orgs_v1_applications_post(orgs, orgs_v1_applications_post_request_inner)
        print("The response of ApplicationsApi->orgs_v1_applications_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ApplicationsApi->orgs_v1_applications_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_applications_post_request_inner** | [**List[OrgsV1ApplicationsPostRequestInner]**](OrgsV1ApplicationsPostRequestInner.md)| Application related APIs | 

### Return type

[**OrgsV1ApplicationsPost200Response**](OrgsV1ApplicationsPost200Response.md)

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


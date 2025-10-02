# openapi_client.PricingApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_pricing_post**](PricingApi.md#orgs_v1_pricing_post) | **POST** /{orgs}/v1/pricing | Pricing related APIs


# **orgs_v1_pricing_post**
> OrgsV1PricingPost200Response orgs_v1_pricing_post(orgs, orgs_v1_pricing_post_request_inner)

Pricing related APIs

### Example


```python
import openapi_client
from openapi_client.models.orgs_v1_pricing_post200_response import OrgsV1PricingPost200Response
from openapi_client.models.orgs_v1_pricing_post_request_inner import OrgsV1PricingPostRequestInner
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
    api_instance = openapi_client.PricingApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_pricing_post_request_inner = [openapi_client.OrgsV1PricingPostRequestInner()] # List[OrgsV1PricingPostRequestInner] | 

    try:
        # Pricing related APIs
        api_response = api_instance.orgs_v1_pricing_post(orgs, orgs_v1_pricing_post_request_inner)
        print("The response of PricingApi->orgs_v1_pricing_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PricingApi->orgs_v1_pricing_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_pricing_post_request_inner** | [**List[OrgsV1PricingPostRequestInner]**](OrgsV1PricingPostRequestInner.md)|  | 

### Return type

[**OrgsV1PricingPost200Response**](OrgsV1PricingPost200Response.md)

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


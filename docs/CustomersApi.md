# entrata_api_client.CustomersApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_customers_post**](CustomersApi.md#orgs_v1_customers_post) | **POST** /{orgs}/v1/customers | Customers


# **orgs_v1_customers_post**
> OrgsV1CustomersPost200Response orgs_v1_customers_post(orgs, orgs_v1_customers_post_request_inner)

Customers

### Example


```python
import entrata_api_client
from entrata_api_client.models.orgs_v1_customers_post200_response import OrgsV1CustomersPost200Response
from entrata_api_client.models.orgs_v1_customers_post_request_inner import OrgsV1CustomersPostRequestInner
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
    api_instance = entrata_api_client.CustomersApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_customers_post_request_inner = [entrata_api_client.OrgsV1CustomersPostRequestInner()] # List[OrgsV1CustomersPostRequestInner] | arPayment related APIs

    try:
        # Customers
        api_response = api_instance.orgs_v1_customers_post(orgs, orgs_v1_customers_post_request_inner)
        print("The response of CustomersApi->orgs_v1_customers_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomersApi->orgs_v1_customers_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_customers_post_request_inner** | [**List[OrgsV1CustomersPostRequestInner]**](OrgsV1CustomersPostRequestInner.md)| arPayment related APIs | 

### Return type

[**OrgsV1CustomersPost200Response**](OrgsV1CustomersPost200Response.md)

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


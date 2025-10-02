# entrata_api_client.VendorsApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_vendors_post**](VendorsApi.md#orgs_v1_vendors_post) | **POST** /{orgs}/v1/vendors | Vendors related APIs


# **orgs_v1_vendors_post**
> OrgsV1VendorsPost200Response orgs_v1_vendors_post(orgs, orgs_v1_vendors_post_request_inner, page_no=page_no, per_page=per_page, x_send_pagination_links=x_send_pagination_links)

Vendors related APIs

## Note:   **Pagination supported APIs**: `getInvoices(r2)`, `getPoReceivingRecords`, `getPurchaseOrders`. 

### Example


```python
import entrata_api_client
from entrata_api_client.models.orgs_v1_vendors_post200_response import OrgsV1VendorsPost200Response
from entrata_api_client.models.orgs_v1_vendors_post_request_inner import OrgsV1VendorsPostRequestInner
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
    api_instance = entrata_api_client.VendorsApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_vendors_post_request_inner = [entrata_api_client.OrgsV1VendorsPostRequestInner()] # List[OrgsV1VendorsPostRequestInner] | 
    page_no = 56 # int | The page number of paginated respons. (optional)
    per_page = 56 # int | The number of items returned in the respnose (optional)
    x_send_pagination_links = 56 # int | Send Pagination Links in Response Body. (optional)

    try:
        # Vendors related APIs
        api_response = api_instance.orgs_v1_vendors_post(orgs, orgs_v1_vendors_post_request_inner, page_no=page_no, per_page=per_page, x_send_pagination_links=x_send_pagination_links)
        print("The response of VendorsApi->orgs_v1_vendors_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling VendorsApi->orgs_v1_vendors_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_vendors_post_request_inner** | [**List[OrgsV1VendorsPostRequestInner]**](OrgsV1VendorsPostRequestInner.md)|  | 
 **page_no** | **int**| The page number of paginated respons. | [optional] 
 **per_page** | **int**| The number of items returned in the respnose | [optional] 
 **x_send_pagination_links** | **int**| Send Pagination Links in Response Body. | [optional] 

### Return type

[**OrgsV1VendorsPost200Response**](OrgsV1VendorsPost200Response.md)

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


# entrata_api_client.LeasingcenterApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_leasingcenter_post**](LeasingcenterApi.md#orgs_v1_leasingcenter_post) | **POST** /{orgs}/v1/leasingcenter | Leasing Center related APIs


# **orgs_v1_leasingcenter_post**
> OrgsV1LeasingcenterPost200Response orgs_v1_leasingcenter_post(orgs, orgs_v1_leasingcenter_post_request_inner, page_no=page_no, per_page=per_page, x_send_pagination_links=x_send_pagination_links)

Leasing Center related APIs

## Note:   **Pagination supported APIs**: `getCallLogs`. 

### Example


```python
import entrata_api_client
from entrata_api_client.models.orgs_v1_leasingcenter_post200_response import OrgsV1LeasingcenterPost200Response
from entrata_api_client.models.orgs_v1_leasingcenter_post_request_inner import OrgsV1LeasingcenterPostRequestInner
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
    api_instance = entrata_api_client.LeasingcenterApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_leasingcenter_post_request_inner = [entrata_api_client.OrgsV1LeasingcenterPostRequestInner()] # List[OrgsV1LeasingcenterPostRequestInner] | 
    page_no = 56 # int | The page number of paginated respons. (optional)
    per_page = 56 # int | The number of items returned in the respnose (optional)
    x_send_pagination_links = 56 # int | Send Pagination Links in Response Body. (optional)

    try:
        # Leasing Center related APIs
        api_response = api_instance.orgs_v1_leasingcenter_post(orgs, orgs_v1_leasingcenter_post_request_inner, page_no=page_no, per_page=per_page, x_send_pagination_links=x_send_pagination_links)
        print("The response of LeasingcenterApi->orgs_v1_leasingcenter_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LeasingcenterApi->orgs_v1_leasingcenter_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_leasingcenter_post_request_inner** | [**List[OrgsV1LeasingcenterPostRequestInner]**](OrgsV1LeasingcenterPostRequestInner.md)|  | 
 **page_no** | **int**| The page number of paginated respons. | [optional] 
 **per_page** | **int**| The number of items returned in the respnose | [optional] 
 **x_send_pagination_links** | **int**| Send Pagination Links in Response Body. | [optional] 

### Return type

[**OrgsV1LeasingcenterPost200Response**](OrgsV1LeasingcenterPost200Response.md)

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


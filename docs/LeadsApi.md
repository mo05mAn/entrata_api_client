# entrata_api_client.LeadsApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_leads_post**](LeadsApi.md#orgs_v1_leads_post) | **POST** /{orgs}/v1/leads | Lead related APIs


# **orgs_v1_leads_post**
> OrgsV1LeadsPost200Response orgs_v1_leads_post(orgs, orgs_v1_leads_post_request_inner, page_no=page_no, per_page=per_page, x_send_pagination_links=x_send_pagination_links)

Lead related APIs

## Note:   **Pagination supported APIs**: `getLeadEvents, getLeads, getMitsLeads, getQuotes`. 

### Example


```python
import entrata_api_client
from entrata_api_client.models.orgs_v1_leads_post200_response import OrgsV1LeadsPost200Response
from entrata_api_client.models.orgs_v1_leads_post_request_inner import OrgsV1LeadsPostRequestInner
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
    api_instance = entrata_api_client.LeadsApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_leads_post_request_inner = [entrata_api_client.OrgsV1LeadsPostRequestInner()] # List[OrgsV1LeadsPostRequestInner] | 
    page_no = 56 # int | The page number of paginated respons. (optional)
    per_page = 56 # int | The number of items returned in the respnose (optional)
    x_send_pagination_links = 56 # int | Send Pagination Links in Response Body. (optional)

    try:
        # Lead related APIs
        api_response = api_instance.orgs_v1_leads_post(orgs, orgs_v1_leads_post_request_inner, page_no=page_no, per_page=per_page, x_send_pagination_links=x_send_pagination_links)
        print("The response of LeadsApi->orgs_v1_leads_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LeadsApi->orgs_v1_leads_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_leads_post_request_inner** | [**List[OrgsV1LeadsPostRequestInner]**](OrgsV1LeadsPostRequestInner.md)|  | 
 **page_no** | **int**| The page number of paginated respons. | [optional] 
 **per_page** | **int**| The number of items returned in the respnose | [optional] 
 **x_send_pagination_links** | **int**| Send Pagination Links in Response Body. | [optional] 

### Return type

[**OrgsV1LeadsPost200Response**](OrgsV1LeadsPost200Response.md)

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


# entrata_api_client.LeasesApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_leases_post**](LeasesApi.md#orgs_v1_leases_post) | **POST** /{orgs}/v1/leases | Leases related APIs


# **orgs_v1_leases_post**
> OrgsV1LeasesPost200Response orgs_v1_leases_post(orgs, orgs_v1_leases_post_request_inner, page_no=page_no, per_page=per_page, x_send_pagination_links=x_send_pagination_links)

Leases related APIs

## Note:   **Pagination supported APIs**: `getLeaseActivities, getLeaseDetails(r2), getLeaseDocumentsList, getParcelAlerts, getLeases(r1), getLease(r2)`. 

### Example


```python
import entrata_api_client
from entrata_api_client.models.orgs_v1_leases_post200_response import OrgsV1LeasesPost200Response
from entrata_api_client.models.orgs_v1_leases_post_request_inner import OrgsV1LeasesPostRequestInner
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
    api_instance = entrata_api_client.LeasesApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    orgs_v1_leases_post_request_inner = [entrata_api_client.OrgsV1LeasesPostRequestInner()] # List[OrgsV1LeasesPostRequestInner] | ## Note:   **sendLeaseDocuments** API accepts files as a form file upload, Please select the option `multipart/form-data` from the Request body dropdown to see further details.  To test the sendLeaseDocuments API or see the additional details, please click the `Try it out` button. 
    page_no = 56 # int | The page number of paginated respons. (optional)
    per_page = 56 # int | The number of items returned in the respnose (optional)
    x_send_pagination_links = 56 # int | Send Pagination Links in Response Body. (optional)

    try:
        # Leases related APIs
        api_response = api_instance.orgs_v1_leases_post(orgs, orgs_v1_leases_post_request_inner, page_no=page_no, per_page=per_page, x_send_pagination_links=x_send_pagination_links)
        print("The response of LeasesApi->orgs_v1_leases_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LeasesApi->orgs_v1_leases_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **orgs_v1_leases_post_request_inner** | [**List[OrgsV1LeasesPostRequestInner]**](OrgsV1LeasesPostRequestInner.md)| ## Note:   **sendLeaseDocuments** API accepts files as a form file upload, Please select the option &#x60;multipart/form-data&#x60; from the Request body dropdown to see further details.  To test the sendLeaseDocuments API or see the additional details, please click the &#x60;Try it out&#x60; button.  | 
 **page_no** | **int**| The page number of paginated respons. | [optional] 
 **per_page** | **int**| The number of items returned in the respnose | [optional] 
 **x_send_pagination_links** | **int**| Send Pagination Links in Response Body. | [optional] 

### Return type

[**OrgsV1LeasesPost200Response**](OrgsV1LeasesPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Success |  -  |
**400** | Failure |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


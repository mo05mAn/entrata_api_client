# entrata_api_client.ArpaymentsApi

All URIs are relative to *https://apis.entrata.com/ext/orgs*

Method | HTTP request | Description
------------- | ------------- | -------------
[**orgs_v1_arpayments_post**](ArpaymentsApi.md#orgs_v1_arpayments_post) | **POST** /{orgs}/v1/arpayments | arPayments


# **orgs_v1_arpayments_post**
> OrgsV1ArpaymentsPost200Response orgs_v1_arpayments_post(orgs, get_ar_payments)

arPayments

### Example


```python
import entrata_api_client
from entrata_api_client.models.get_ar_payments import GetArPayments
from entrata_api_client.models.orgs_v1_arpayments_post200_response import OrgsV1ArpaymentsPost200Response
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
    api_instance = entrata_api_client.ArpaymentsApi(api_client)
    orgs = 'orgs_example' # str | Client subdomain.
    get_ar_payments = entrata_api_client.GetArPayments() # GetArPayments | Retrieves AR payments details with reference to a Payment ID and for a selected date range.

    try:
        # arPayments
        api_response = api_instance.orgs_v1_arpayments_post(orgs, get_ar_payments)
        print("The response of ArpaymentsApi->orgs_v1_arpayments_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ArpaymentsApi->orgs_v1_arpayments_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgs** | **str**| Client subdomain. | 
 **get_ar_payments** | [**GetArPayments**](GetArPayments.md)| Retrieves AR payments details with reference to a Payment ID and for a selected date range. | 

### Return type

[**OrgsV1ArpaymentsPost200Response**](OrgsV1ArpaymentsPost200Response.md)

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


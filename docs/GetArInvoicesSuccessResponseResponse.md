# GetArInvoicesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary identifier used to trace or track the request. | [optional] 
**code** | **int** | Successful response code. | 
**result** | [**GetArInvoicesSuccessResponseResponseResult**](GetArInvoicesSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_ar_invoices_success_response_response import GetArInvoicesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetArInvoicesSuccessResponseResponse from a JSON string
get_ar_invoices_success_response_response_instance = GetArInvoicesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetArInvoicesSuccessResponseResponse.to_json())

# convert the object into a dict
get_ar_invoices_success_response_response_dict = get_ar_invoices_success_response_response_instance.to_dict()
# create an instance of GetArInvoicesSuccessResponseResponse from a dict
get_ar_invoices_success_response_response_from_dict = GetArInvoicesSuccessResponseResponse.from_dict(get_ar_invoices_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



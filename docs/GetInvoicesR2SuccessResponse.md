# GetInvoicesR2SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | [optional] 
**code** | **str** | Response code indicating success | [optional] 
**result** | [**GetInvoicesR2SuccessResponseResult**](GetInvoicesR2SuccessResponseResult.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_invoices_r2_success_response import GetInvoicesR2SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2SuccessResponse from a JSON string
get_invoices_r2_success_response_instance = GetInvoicesR2SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2SuccessResponse.to_json())

# convert the object into a dict
get_invoices_r2_success_response_dict = get_invoices_r2_success_response_instance.to_dict()
# create an instance of GetInvoicesR2SuccessResponse from a dict
get_invoices_r2_success_response_from_dict = GetInvoicesR2SuccessResponse.from_dict(get_invoices_r2_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



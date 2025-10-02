# GetInvoicesR1SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | [optional] 
**code** | **str** | Success response code | [optional] 
**result** | [**GetInvoicesR1SuccessResponseResult**](GetInvoicesR1SuccessResponseResult.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_invoices_r1_success_response import GetInvoicesR1SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponse from a JSON string
get_invoices_r1_success_response_instance = GetInvoicesR1SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponse.to_json())

# convert the object into a dict
get_invoices_r1_success_response_dict = get_invoices_r1_success_response_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponse from a dict
get_invoices_r1_success_response_from_dict = GetInvoicesR1SuccessResponse.from_dict(get_invoices_r1_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



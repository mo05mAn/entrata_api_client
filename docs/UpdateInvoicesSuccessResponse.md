# UpdateInvoicesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result** | [**UpdateInvoicesSuccessResponseResult**](UpdateInvoicesSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_invoices_success_response import UpdateInvoicesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateInvoicesSuccessResponse from a JSON string
update_invoices_success_response_instance = UpdateInvoicesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateInvoicesSuccessResponse.to_json())

# convert the object into a dict
update_invoices_success_response_dict = update_invoices_success_response_instance.to_dict()
# create an instance of UpdateInvoicesSuccessResponse from a dict
update_invoices_success_response_from_dict = UpdateInvoicesSuccessResponse.from_dict(update_invoices_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



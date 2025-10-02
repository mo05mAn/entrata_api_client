# UpdateInvoicesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_headers** | [**UpdateInvoicesSuccessResponseResultApHeaders**](UpdateInvoicesSuccessResponseResultApHeaders.md) |  | [optional] 

## Example

```python
from openapi_client.models.update_invoices_success_response_result import UpdateInvoicesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateInvoicesSuccessResponseResult from a JSON string
update_invoices_success_response_result_instance = UpdateInvoicesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateInvoicesSuccessResponseResult.to_json())

# convert the object into a dict
update_invoices_success_response_result_dict = update_invoices_success_response_result_instance.to_dict()
# create an instance of UpdateInvoicesSuccessResponseResult from a dict
update_invoices_success_response_result_from_dict = UpdateInvoicesSuccessResponseResult.from_dict(update_invoices_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



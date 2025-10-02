# SendInvoicesR2SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result** | [**SendInvoicesR2SuccessResponseResult**](SendInvoicesR2SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_invoices_r2_success_response import SendInvoicesR2SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR2SuccessResponse from a JSON string
send_invoices_r2_success_response_instance = SendInvoicesR2SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR2SuccessResponse.to_json())

# convert the object into a dict
send_invoices_r2_success_response_dict = send_invoices_r2_success_response_instance.to_dict()
# create an instance of SendInvoicesR2SuccessResponse from a dict
send_invoices_r2_success_response_from_dict = SendInvoicesR2SuccessResponse.from_dict(send_invoices_r2_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



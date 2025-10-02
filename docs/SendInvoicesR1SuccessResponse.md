# SendInvoicesR1SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result** | [**SendInvoicesR1SuccessResponseResult**](SendInvoicesR1SuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_invoices_r1_success_response import SendInvoicesR1SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR1SuccessResponse from a JSON string
send_invoices_r1_success_response_instance = SendInvoicesR1SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR1SuccessResponse.to_json())

# convert the object into a dict
send_invoices_r1_success_response_dict = send_invoices_r1_success_response_instance.to_dict()
# create an instance of SendInvoicesR1SuccessResponse from a dict
send_invoices_r1_success_response_from_dict = SendInvoicesR1SuccessResponse.from_dict(send_invoices_r1_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



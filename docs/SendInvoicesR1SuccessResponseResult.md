# SendInvoicesR1SuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_batch** | [**SendInvoicesR1SuccessResponseResultApBatch**](SendInvoicesR1SuccessResponseResultApBatch.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_invoices_r1_success_response_result import SendInvoicesR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR1SuccessResponseResult from a JSON string
send_invoices_r1_success_response_result_instance = SendInvoicesR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR1SuccessResponseResult.to_json())

# convert the object into a dict
send_invoices_r1_success_response_result_dict = send_invoices_r1_success_response_result_instance.to_dict()
# create an instance of SendInvoicesR1SuccessResponseResult from a dict
send_invoices_r1_success_response_result_from_dict = SendInvoicesR1SuccessResponseResult.from_dict(send_invoices_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



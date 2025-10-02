# SendInvoicesR1SuccessResponseResultApBatch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | [**SendInvoicesR1SuccessResponseResultApBatchAttributes**](SendInvoicesR1SuccessResponseResultApBatchAttributes.md) |  | [optional] 
**ap_headers** | [**SendInvoicesR1SuccessResponseResultApBatchApHeaders**](SendInvoicesR1SuccessResponseResultApBatchApHeaders.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_invoices_r1_success_response_result_ap_batch import SendInvoicesR1SuccessResponseResultApBatch

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR1SuccessResponseResultApBatch from a JSON string
send_invoices_r1_success_response_result_ap_batch_instance = SendInvoicesR1SuccessResponseResultApBatch.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR1SuccessResponseResultApBatch.to_json())

# convert the object into a dict
send_invoices_r1_success_response_result_ap_batch_dict = send_invoices_r1_success_response_result_ap_batch_instance.to_dict()
# create an instance of SendInvoicesR1SuccessResponseResultApBatch from a dict
send_invoices_r1_success_response_result_ap_batch_from_dict = SendInvoicesR1SuccessResponseResultApBatch.from_dict(send_invoices_r1_success_response_result_ap_batch_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



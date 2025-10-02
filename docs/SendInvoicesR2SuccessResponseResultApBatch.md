# SendInvoicesR2SuccessResponseResultApBatch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_batch_id** | **int** | Unique identifier for the AP batch. | [optional] 
**ap_headers** | [**SendInvoicesR2SuccessResponseResultApBatchApHeaders**](SendInvoicesR2SuccessResponseResultApBatchApHeaders.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_invoices_r2_success_response_result_ap_batch import SendInvoicesR2SuccessResponseResultApBatch

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR2SuccessResponseResultApBatch from a JSON string
send_invoices_r2_success_response_result_ap_batch_instance = SendInvoicesR2SuccessResponseResultApBatch.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR2SuccessResponseResultApBatch.to_json())

# convert the object into a dict
send_invoices_r2_success_response_result_ap_batch_dict = send_invoices_r2_success_response_result_ap_batch_instance.to_dict()
# create an instance of SendInvoicesR2SuccessResponseResultApBatch from a dict
send_invoices_r2_success_response_result_ap_batch_from_dict = SendInvoicesR2SuccessResponseResultApBatch.from_dict(send_invoices_r2_success_response_result_ap_batch_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



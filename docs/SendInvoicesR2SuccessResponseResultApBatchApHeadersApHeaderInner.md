# SendInvoicesR2SuccessResponseResultApBatchApHeadersApHeaderInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Node identifier for the AP header. | [optional] 
**invoice_number** | **str** | The invoice number associated with the AP header. | [optional] 
**ap_header_id** | **int** | Unique identifier for the AP header. | [optional] 
**status** | **str** | Status of the AP header insertion. | [optional] 
**message** | **str** | Message indicating the result of the AP header insertion. | [optional] 

## Example

```python
from entrata_api_client.models.send_invoices_r2_success_response_result_ap_batch_ap_headers_ap_header_inner import SendInvoicesR2SuccessResponseResultApBatchApHeadersApHeaderInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR2SuccessResponseResultApBatchApHeadersApHeaderInner from a JSON string
send_invoices_r2_success_response_result_ap_batch_ap_headers_ap_header_inner_instance = SendInvoicesR2SuccessResponseResultApBatchApHeadersApHeaderInner.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR2SuccessResponseResultApBatchApHeadersApHeaderInner.to_json())

# convert the object into a dict
send_invoices_r2_success_response_result_ap_batch_ap_headers_ap_header_inner_dict = send_invoices_r2_success_response_result_ap_batch_ap_headers_ap_header_inner_instance.to_dict()
# create an instance of SendInvoicesR2SuccessResponseResultApBatchApHeadersApHeaderInner from a dict
send_invoices_r2_success_response_result_ap_batch_ap_headers_ap_header_inner_from_dict = SendInvoicesR2SuccessResponseResultApBatchApHeadersApHeaderInner.from_dict(send_invoices_r2_success_response_result_ap_batch_ap_headers_ap_header_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



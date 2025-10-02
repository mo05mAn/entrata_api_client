# SendInvoicesR1SuccessResponseResultApBatchApHeadersApHeaderInnerAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invoice_number** | **str** | The invoice number. | [optional] 
**reference_id** | **str** | The unique reference ID for the AP Header. | [optional] 
**status** | **str** | Status of the AP Header insertion. | [optional] 
**message** | **str** | Message indicating the result of the AP Header insertion. | [optional] 

## Example

```python
from openapi_client.models.send_invoices_r1_success_response_result_ap_batch_ap_headers_ap_header_inner_attributes import SendInvoicesR1SuccessResponseResultApBatchApHeadersApHeaderInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR1SuccessResponseResultApBatchApHeadersApHeaderInnerAttributes from a JSON string
send_invoices_r1_success_response_result_ap_batch_ap_headers_ap_header_inner_attributes_instance = SendInvoicesR1SuccessResponseResultApBatchApHeadersApHeaderInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR1SuccessResponseResultApBatchApHeadersApHeaderInnerAttributes.to_json())

# convert the object into a dict
send_invoices_r1_success_response_result_ap_batch_ap_headers_ap_header_inner_attributes_dict = send_invoices_r1_success_response_result_ap_batch_ap_headers_ap_header_inner_attributes_instance.to_dict()
# create an instance of SendInvoicesR1SuccessResponseResultApBatchApHeadersApHeaderInnerAttributes from a dict
send_invoices_r1_success_response_result_ap_batch_ap_headers_ap_header_inner_attributes_from_dict = SendInvoicesR1SuccessResponseResultApBatchApHeadersApHeaderInnerAttributes.from_dict(send_invoices_r1_success_response_result_ap_batch_ap_headers_ap_header_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



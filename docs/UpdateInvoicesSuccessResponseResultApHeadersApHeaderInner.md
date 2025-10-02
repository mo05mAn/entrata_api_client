# UpdateInvoicesSuccessResponseResultApHeadersApHeaderInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reference_id** | **str** | Unique identifier for the invoice update request. | [optional] 
**status** | **str** | Status of the invoice update. | [optional] 
**message** | **str** | Message indicating the result of the invoice update. | [optional] 

## Example

```python
from openapi_client.models.update_invoices_success_response_result_ap_headers_ap_header_inner import UpdateInvoicesSuccessResponseResultApHeadersApHeaderInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateInvoicesSuccessResponseResultApHeadersApHeaderInner from a JSON string
update_invoices_success_response_result_ap_headers_ap_header_inner_instance = UpdateInvoicesSuccessResponseResultApHeadersApHeaderInner.from_json(json)
# print the JSON string representation of the object
print(UpdateInvoicesSuccessResponseResultApHeadersApHeaderInner.to_json())

# convert the object into a dict
update_invoices_success_response_result_ap_headers_ap_header_inner_dict = update_invoices_success_response_result_ap_headers_ap_header_inner_instance.to_dict()
# create an instance of UpdateInvoicesSuccessResponseResultApHeadersApHeaderInner from a dict
update_invoices_success_response_result_ap_headers_ap_header_inner_from_dict = UpdateInvoicesSuccessResponseResultApHeadersApHeaderInner.from_dict(update_invoices_success_response_result_ap_headers_ap_header_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



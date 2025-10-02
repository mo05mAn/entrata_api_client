# SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Node identifier for the AP header. | [optional] 
**status** | **str** | Status of the AP header insertion. | [optional] 
**ap_header_id** | **int** | Unique identifier for the AP header. | [optional] 
**po_number** | **int** | Purchase Order number associated with the AP header. | [optional] 
**message** | **str** | Message indicating the result of the AP header insertion. | [optional] 

## Example

```python
from openapi_client.models.send_purchase_orders_success_response_result_ap_headers_ap_header_inner import SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner from a JSON string
send_purchase_orders_success_response_result_ap_headers_ap_header_inner_instance = SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner.from_json(json)
# print the JSON string representation of the object
print(SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner.to_json())

# convert the object into a dict
send_purchase_orders_success_response_result_ap_headers_ap_header_inner_dict = send_purchase_orders_success_response_result_ap_headers_ap_header_inner_instance.to_dict()
# create an instance of SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner from a dict
send_purchase_orders_success_response_result_ap_headers_ap_header_inner_from_dict = SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner.from_dict(send_purchase_orders_success_response_result_ap_headers_ap_header_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



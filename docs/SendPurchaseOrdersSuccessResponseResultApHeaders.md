# SendPurchaseOrdersSuccessResponseResultApHeaders


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_header** | [**List[SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner]**](SendPurchaseOrdersSuccessResponseResultApHeadersApHeaderInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_purchase_orders_success_response_result_ap_headers import SendPurchaseOrdersSuccessResponseResultApHeaders

# TODO update the JSON string below
json = "{}"
# create an instance of SendPurchaseOrdersSuccessResponseResultApHeaders from a JSON string
send_purchase_orders_success_response_result_ap_headers_instance = SendPurchaseOrdersSuccessResponseResultApHeaders.from_json(json)
# print the JSON string representation of the object
print(SendPurchaseOrdersSuccessResponseResultApHeaders.to_json())

# convert the object into a dict
send_purchase_orders_success_response_result_ap_headers_dict = send_purchase_orders_success_response_result_ap_headers_instance.to_dict()
# create an instance of SendPurchaseOrdersSuccessResponseResultApHeaders from a dict
send_purchase_orders_success_response_result_ap_headers_from_dict = SendPurchaseOrdersSuccessResponseResultApHeaders.from_dict(send_purchase_orders_success_response_result_ap_headers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



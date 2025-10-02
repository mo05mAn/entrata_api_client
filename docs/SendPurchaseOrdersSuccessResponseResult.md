# SendPurchaseOrdersSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_headers** | [**SendPurchaseOrdersSuccessResponseResultApHeaders**](SendPurchaseOrdersSuccessResponseResultApHeaders.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_purchase_orders_success_response_result import SendPurchaseOrdersSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendPurchaseOrdersSuccessResponseResult from a JSON string
send_purchase_orders_success_response_result_instance = SendPurchaseOrdersSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendPurchaseOrdersSuccessResponseResult.to_json())

# convert the object into a dict
send_purchase_orders_success_response_result_dict = send_purchase_orders_success_response_result_instance.to_dict()
# create an instance of SendPurchaseOrdersSuccessResponseResult from a dict
send_purchase_orders_success_response_result_from_dict = SendPurchaseOrdersSuccessResponseResult.from_dict(send_purchase_orders_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



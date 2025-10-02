# SendPurchaseOrdersMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendPurchaseOrdersMethodParams**](SendPurchaseOrdersMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_purchase_orders_method import SendPurchaseOrdersMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendPurchaseOrdersMethod from a JSON string
send_purchase_orders_method_instance = SendPurchaseOrdersMethod.from_json(json)
# print the JSON string representation of the object
print(SendPurchaseOrdersMethod.to_json())

# convert the object into a dict
send_purchase_orders_method_dict = send_purchase_orders_method_instance.to_dict()
# create an instance of SendPurchaseOrdersMethod from a dict
send_purchase_orders_method_from_dict = SendPurchaseOrdersMethod.from_dict(send_purchase_orders_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



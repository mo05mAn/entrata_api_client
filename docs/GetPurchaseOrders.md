# GetPurchaseOrders


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetPurchaseOrdersMethod**](GetPurchaseOrdersMethod.md) |  | 

## Example

```python
from openapi_client.models.get_purchase_orders import GetPurchaseOrders

# TODO update the JSON string below
json = "{}"
# create an instance of GetPurchaseOrders from a JSON string
get_purchase_orders_instance = GetPurchaseOrders.from_json(json)
# print the JSON string representation of the object
print(GetPurchaseOrders.to_json())

# convert the object into a dict
get_purchase_orders_dict = get_purchase_orders_instance.to_dict()
# create an instance of GetPurchaseOrders from a dict
get_purchase_orders_from_dict = GetPurchaseOrders.from_dict(get_purchase_orders_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



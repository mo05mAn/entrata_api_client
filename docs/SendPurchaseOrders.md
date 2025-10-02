# SendPurchaseOrders


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendPurchaseOrdersMethod**](SendPurchaseOrdersMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_purchase_orders import SendPurchaseOrders

# TODO update the JSON string below
json = "{}"
# create an instance of SendPurchaseOrders from a JSON string
send_purchase_orders_instance = SendPurchaseOrders.from_json(json)
# print the JSON string representation of the object
print(SendPurchaseOrders.to_json())

# convert the object into a dict
send_purchase_orders_dict = send_purchase_orders_instance.to_dict()
# create an instance of SendPurchaseOrders from a dict
send_purchase_orders_from_dict = SendPurchaseOrders.from_dict(send_purchase_orders_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



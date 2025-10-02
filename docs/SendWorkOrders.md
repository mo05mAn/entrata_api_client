# SendWorkOrders


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendWorkOrdersMethod**](SendWorkOrdersMethod.md) |  | 

## Example

```python
from openapi_client.models.send_work_orders import SendWorkOrders

# TODO update the JSON string below
json = "{}"
# create an instance of SendWorkOrders from a JSON string
send_work_orders_instance = SendWorkOrders.from_json(json)
# print the JSON string representation of the object
print(SendWorkOrders.to_json())

# convert the object into a dict
send_work_orders_dict = send_work_orders_instance.to_dict()
# create an instance of SendWorkOrders from a dict
send_work_orders_from_dict = SendWorkOrders.from_dict(send_work_orders_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



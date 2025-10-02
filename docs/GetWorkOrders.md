# GetWorkOrders


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetWorkOrdersMethod**](GetWorkOrdersMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_work_orders import GetWorkOrders

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrders from a JSON string
get_work_orders_instance = GetWorkOrders.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrders.to_json())

# convert the object into a dict
get_work_orders_dict = get_work_orders_instance.to_dict()
# create an instance of GetWorkOrders from a dict
get_work_orders_from_dict = GetWorkOrders.from_dict(get_work_orders_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



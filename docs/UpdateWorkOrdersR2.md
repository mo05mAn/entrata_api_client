# UpdateWorkOrdersR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateWorkOrdersR2Method**](UpdateWorkOrdersR2Method.md) |  | 

## Example

```python
from openapi_client.models.update_work_orders_r2 import UpdateWorkOrdersR2

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWorkOrdersR2 from a JSON string
update_work_orders_r2_instance = UpdateWorkOrdersR2.from_json(json)
# print the JSON string representation of the object
print(UpdateWorkOrdersR2.to_json())

# convert the object into a dict
update_work_orders_r2_dict = update_work_orders_r2_instance.to_dict()
# create an instance of UpdateWorkOrdersR2 from a dict
update_work_orders_r2_from_dict = UpdateWorkOrdersR2.from_dict(update_work_orders_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



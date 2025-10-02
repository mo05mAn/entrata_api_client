# UpdateWorkOrdersR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateWorkOrdersR1Method**](UpdateWorkOrdersR1Method.md) |  | 

## Example

```python
from entrata_api_client.models.update_work_orders_r1 import UpdateWorkOrdersR1

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWorkOrdersR1 from a JSON string
update_work_orders_r1_instance = UpdateWorkOrdersR1.from_json(json)
# print the JSON string representation of the object
print(UpdateWorkOrdersR1.to_json())

# convert the object into a dict
update_work_orders_r1_dict = update_work_orders_r1_instance.to_dict()
# create an instance of UpdateWorkOrdersR1 from a dict
update_work_orders_r1_from_dict = UpdateWorkOrdersR1.from_dict(update_work_orders_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



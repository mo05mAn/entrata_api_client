# GetWorkOrderPickLists


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetWorkOrderPickListsMethod**](GetWorkOrderPickListsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_work_order_pick_lists import GetWorkOrderPickLists

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrderPickLists from a JSON string
get_work_order_pick_lists_instance = GetWorkOrderPickLists.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrderPickLists.to_json())

# convert the object into a dict
get_work_order_pick_lists_dict = get_work_order_pick_lists_instance.to_dict()
# create an instance of GetWorkOrderPickLists from a dict
get_work_order_pick_lists_from_dict = GetWorkOrderPickLists.from_dict(get_work_order_pick_lists_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetWorkOrderPickListsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetWorkOrderPickListsMethodParams**](GetWorkOrderPickListsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_work_order_pick_lists_method import GetWorkOrderPickListsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrderPickListsMethod from a JSON string
get_work_order_pick_lists_method_instance = GetWorkOrderPickListsMethod.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrderPickListsMethod.to_json())

# convert the object into a dict
get_work_order_pick_lists_method_dict = get_work_order_pick_lists_method_instance.to_dict()
# create an instance of GetWorkOrderPickListsMethod from a dict
get_work_order_pick_lists_method_from_dict = GetWorkOrderPickListsMethod.from_dict(get_work_order_pick_lists_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



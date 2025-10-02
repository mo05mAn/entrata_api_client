# GetPropertyPickListsR2Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPropertyPickListsR1MethodParams**](GetPropertyPickListsR1MethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_property_pick_lists_r2_method import GetPropertyPickListsR2Method

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR2Method from a JSON string
get_property_pick_lists_r2_method_instance = GetPropertyPickListsR2Method.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR2Method.to_json())

# convert the object into a dict
get_property_pick_lists_r2_method_dict = get_property_pick_lists_r2_method_instance.to_dict()
# create an instance of GetPropertyPickListsR2Method from a dict
get_property_pick_lists_r2_method_from_dict = GetPropertyPickListsR2Method.from_dict(get_property_pick_lists_r2_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



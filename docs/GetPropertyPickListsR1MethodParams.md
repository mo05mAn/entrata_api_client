# GetPropertyPickListsR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. Comman seperated list of properties | [optional] 

## Example

```python
from entrata_api_client.models.get_property_pick_lists_r1_method_params import GetPropertyPickListsR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR1MethodParams from a JSON string
get_property_pick_lists_r1_method_params_instance = GetPropertyPickListsR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR1MethodParams.to_json())

# convert the object into a dict
get_property_pick_lists_r1_method_params_dict = get_property_pick_lists_r1_method_params_instance.to_dict()
# create an instance of GetPropertyPickListsR1MethodParams from a dict
get_property_pick_lists_r1_method_params_from_dict = GetPropertyPickListsR1MethodParams.from_dict(get_property_pick_lists_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



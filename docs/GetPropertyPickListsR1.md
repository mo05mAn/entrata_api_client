# GetPropertyPickListsR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetPropertyPickListsR1Method**](GetPropertyPickListsR1Method.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_pick_lists_r1 import GetPropertyPickListsR1

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR1 from a JSON string
get_property_pick_lists_r1_instance = GetPropertyPickListsR1.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR1.to_json())

# convert the object into a dict
get_property_pick_lists_r1_dict = get_property_pick_lists_r1_instance.to_dict()
# create an instance of GetPropertyPickListsR1 from a dict
get_property_pick_lists_r1_from_dict = GetPropertyPickListsR1.from_dict(get_property_pick_lists_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



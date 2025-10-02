# GetGlTreesR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetGlTreesR1Method**](GetGlTreesR1Method.md) |  | 

## Example

```python
from entrata_api_client.models.get_gl_trees_r1 import GetGlTreesR1

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTreesR1 from a JSON string
get_gl_trees_r1_instance = GetGlTreesR1.from_json(json)
# print the JSON string representation of the object
print(GetGlTreesR1.to_json())

# convert the object into a dict
get_gl_trees_r1_dict = get_gl_trees_r1_instance.to_dict()
# create an instance of GetGlTreesR1 from a dict
get_gl_trees_r1_from_dict = GetGlTreesR1.from_dict(get_gl_trees_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



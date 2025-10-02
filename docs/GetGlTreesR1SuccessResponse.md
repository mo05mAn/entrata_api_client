# GetGlTreesR1SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**result** | [**GetGlTreesR1SuccessResponseResult**](GetGlTreesR1SuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_gl_trees_r1_success_response import GetGlTreesR1SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTreesR1SuccessResponse from a JSON string
get_gl_trees_r1_success_response_instance = GetGlTreesR1SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetGlTreesR1SuccessResponse.to_json())

# convert the object into a dict
get_gl_trees_r1_success_response_dict = get_gl_trees_r1_success_response_instance.to_dict()
# create an instance of GetGlTreesR1SuccessResponse from a dict
get_gl_trees_r1_success_response_from_dict = GetGlTreesR1SuccessResponse.from_dict(get_gl_trees_r1_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



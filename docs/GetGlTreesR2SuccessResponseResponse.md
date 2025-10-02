# GetGlTreesR2SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | [optional] 
**code** | **int** | HTTP status code indicating the result of the request | [optional] 
**result** | [**GetGlTreesR2SuccessResponseResponseResult**](GetGlTreesR2SuccessResponseResponseResult.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_gl_trees_r2_success_response_response import GetGlTreesR2SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTreesR2SuccessResponseResponse from a JSON string
get_gl_trees_r2_success_response_response_instance = GetGlTreesR2SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetGlTreesR2SuccessResponseResponse.to_json())

# convert the object into a dict
get_gl_trees_r2_success_response_response_dict = get_gl_trees_r2_success_response_response_instance.to_dict()
# create an instance of GetGlTreesR2SuccessResponseResponse from a dict
get_gl_trees_r2_success_response_response_from_dict = GetGlTreesR2SuccessResponseResponse.from_dict(get_gl_trees_r2_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



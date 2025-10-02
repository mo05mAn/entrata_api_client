# GetPropertyPickListsR2SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **int** | Unique identifier for the request | 
**code** | **int** | Success response code | 
**result** | [**GetPropertyPickListsR2SuccessResponseResult**](GetPropertyPickListsR2SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_pick_lists_r2_success_response import GetPropertyPickListsR2SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR2SuccessResponse from a JSON string
get_property_pick_lists_r2_success_response_instance = GetPropertyPickListsR2SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR2SuccessResponse.to_json())

# convert the object into a dict
get_property_pick_lists_r2_success_response_dict = get_property_pick_lists_r2_success_response_instance.to_dict()
# create an instance of GetPropertyPickListsR2SuccessResponse from a dict
get_property_pick_lists_r2_success_response_from_dict = GetPropertyPickListsR2SuccessResponse.from_dict(get_property_pick_lists_r2_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



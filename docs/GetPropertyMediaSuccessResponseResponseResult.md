# GetPropertyMediaSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | Property identifier | 
**media** | [**List[MediaItem]**](MediaItem.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_media_success_response_response_result import GetPropertyMediaSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyMediaSuccessResponseResponseResult from a JSON string
get_property_media_success_response_response_result_instance = GetPropertyMediaSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPropertyMediaSuccessResponseResponseResult.to_json())

# convert the object into a dict
get_property_media_success_response_response_result_dict = get_property_media_success_response_response_result_instance.to_dict()
# create an instance of GetPropertyMediaSuccessResponseResponseResult from a dict
get_property_media_success_response_response_result_from_dict = GetPropertyMediaSuccessResponseResponseResult.from_dict(get_property_media_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



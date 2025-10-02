# GetPropertyMediaSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **int** | Response code indicating success | 
**result** | [**GetPropertyMediaSuccessResponseResponseResult**](GetPropertyMediaSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_property_media_success_response_response import GetPropertyMediaSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyMediaSuccessResponseResponse from a JSON string
get_property_media_success_response_response_instance = GetPropertyMediaSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetPropertyMediaSuccessResponseResponse.to_json())

# convert the object into a dict
get_property_media_success_response_response_dict = get_property_media_success_response_response_instance.to_dict()
# create an instance of GetPropertyMediaSuccessResponseResponse from a dict
get_property_media_success_response_response_from_dict = GetPropertyMediaSuccessResponseResponse.from_dict(get_property_media_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



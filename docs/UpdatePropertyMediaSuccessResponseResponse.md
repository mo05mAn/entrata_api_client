# UpdatePropertyMediaSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**code** | **int** | Response code indicating success | 
**result** | [**UpdatePropertyMediaSuccessResponseResponseResult**](UpdatePropertyMediaSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.update_property_media_success_response_response import UpdatePropertyMediaSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePropertyMediaSuccessResponseResponse from a JSON string
update_property_media_success_response_response_instance = UpdatePropertyMediaSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(UpdatePropertyMediaSuccessResponseResponse.to_json())

# convert the object into a dict
update_property_media_success_response_response_dict = update_property_media_success_response_response_instance.to_dict()
# create an instance of UpdatePropertyMediaSuccessResponseResponse from a dict
update_property_media_success_response_response_from_dict = UpdatePropertyMediaSuccessResponseResponse.from_dict(update_property_media_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



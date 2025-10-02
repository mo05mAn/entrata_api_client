# DeletePropertyMediaSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**code** | **int** | Response code indicating success | 
**result** | [**DeletePropertyMediaSuccessResponseResponseResult**](DeletePropertyMediaSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.delete_property_media_success_response_response import DeletePropertyMediaSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of DeletePropertyMediaSuccessResponseResponse from a JSON string
delete_property_media_success_response_response_instance = DeletePropertyMediaSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(DeletePropertyMediaSuccessResponseResponse.to_json())

# convert the object into a dict
delete_property_media_success_response_response_dict = delete_property_media_success_response_response_instance.to_dict()
# create an instance of DeletePropertyMediaSuccessResponseResponse from a dict
delete_property_media_success_response_response_from_dict = DeletePropertyMediaSuccessResponseResponse.from_dict(delete_property_media_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



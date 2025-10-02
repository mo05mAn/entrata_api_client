# SendPropertyMediaSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**code** | **int** | Response code indicating success | 
**result** | [**SendPropertyMediaSuccessResponseResponseResult**](SendPropertyMediaSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_property_media_success_response_response import SendPropertyMediaSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyMediaSuccessResponseResponse from a JSON string
send_property_media_success_response_response_instance = SendPropertyMediaSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendPropertyMediaSuccessResponseResponse.to_json())

# convert the object into a dict
send_property_media_success_response_response_dict = send_property_media_success_response_response_instance.to_dict()
# create an instance of SendPropertyMediaSuccessResponseResponse from a dict
send_property_media_success_response_response_from_dict = SendPropertyMediaSuccessResponseResponse.from_dict(send_property_media_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



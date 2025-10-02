# GetPropertyAnnouncementsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **int** | Unique identifier for the request | 
**result** | [**GetPropertyAnnouncementsSuccessResponseResult**](GetPropertyAnnouncementsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_property_announcements_success_response import GetPropertyAnnouncementsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAnnouncementsSuccessResponse from a JSON string
get_property_announcements_success_response_instance = GetPropertyAnnouncementsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAnnouncementsSuccessResponse.to_json())

# convert the object into a dict
get_property_announcements_success_response_dict = get_property_announcements_success_response_instance.to_dict()
# create an instance of GetPropertyAnnouncementsSuccessResponse from a dict
get_property_announcements_success_response_from_dict = GetPropertyAnnouncementsSuccessResponse.from_dict(get_property_announcements_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



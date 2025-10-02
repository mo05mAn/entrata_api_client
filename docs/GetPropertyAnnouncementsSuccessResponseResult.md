# GetPropertyAnnouncementsSuccessResponseResult

Contains the announcements information

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**announcements** | [**GetPropertyAnnouncementsSuccessResponseResultAnnouncements**](GetPropertyAnnouncementsSuccessResponseResultAnnouncements.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_announcements_success_response_result import GetPropertyAnnouncementsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAnnouncementsSuccessResponseResult from a JSON string
get_property_announcements_success_response_result_instance = GetPropertyAnnouncementsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAnnouncementsSuccessResponseResult.to_json())

# convert the object into a dict
get_property_announcements_success_response_result_dict = get_property_announcements_success_response_result_instance.to_dict()
# create an instance of GetPropertyAnnouncementsSuccessResponseResult from a dict
get_property_announcements_success_response_result_from_dict = GetPropertyAnnouncementsSuccessResponseResult.from_dict(get_property_announcements_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



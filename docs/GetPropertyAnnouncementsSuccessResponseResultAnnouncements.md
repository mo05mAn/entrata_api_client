# GetPropertyAnnouncementsSuccessResponseResultAnnouncements

Details of the announcements

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**announcement** | [**List[GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner]**](GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner.md) | List of announcements | 

## Example

```python
from entrata_api_client.models.get_property_announcements_success_response_result_announcements import GetPropertyAnnouncementsSuccessResponseResultAnnouncements

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAnnouncementsSuccessResponseResultAnnouncements from a JSON string
get_property_announcements_success_response_result_announcements_instance = GetPropertyAnnouncementsSuccessResponseResultAnnouncements.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAnnouncementsSuccessResponseResultAnnouncements.to_json())

# convert the object into a dict
get_property_announcements_success_response_result_announcements_dict = get_property_announcements_success_response_result_announcements_instance.to_dict()
# create an instance of GetPropertyAnnouncementsSuccessResponseResultAnnouncements from a dict
get_property_announcements_success_response_result_announcements_from_dict = GetPropertyAnnouncementsSuccessResponseResultAnnouncements.from_dict(get_property_announcements_success_response_result_announcements_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



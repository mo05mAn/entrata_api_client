# GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | [**GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInnerAttributes**](GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInnerAttributes.md) |  | [optional] 
**announcement_type_id** | **int** | Identifier for the type of announcement | 
**frequency_id** | **int** | Identifier for the frequency of the announcement | 
**title** | **str** | Title of the announcement | 
**description** | **str** | Description of the announcement | 
**start_date** | **date** | The start date of the announcement | 
**end_date** | **date** | The end date of the announcement | 

## Example

```python
from openapi_client.models.get_property_announcements_success_response_result_announcements_announcement_inner import GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner from a JSON string
get_property_announcements_success_response_result_announcements_announcement_inner_instance = GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner.to_json())

# convert the object into a dict
get_property_announcements_success_response_result_announcements_announcement_inner_dict = get_property_announcements_success_response_result_announcements_announcement_inner_instance.to_dict()
# create an instance of GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner from a dict
get_property_announcements_success_response_result_announcements_announcement_inner_from_dict = GetPropertyAnnouncementsSuccessResponseResultAnnouncementsAnnouncementInner.from_dict(get_property_announcements_success_response_result_announcements_announcement_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetPropertyAnnouncements


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetPropertyAnnouncementsMethod**](GetPropertyAnnouncementsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_property_announcements import GetPropertyAnnouncements

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAnnouncements from a JSON string
get_property_announcements_instance = GetPropertyAnnouncements.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAnnouncements.to_json())

# convert the object into a dict
get_property_announcements_dict = get_property_announcements_instance.to_dict()
# create an instance of GetPropertyAnnouncements from a dict
get_property_announcements_from_dict = GetPropertyAnnouncements.from_dict(get_property_announcements_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



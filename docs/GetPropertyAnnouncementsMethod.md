# GetPropertyAnnouncementsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPropertyAddOnsMethodParams**](GetPropertyAddOnsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_property_announcements_method import GetPropertyAnnouncementsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAnnouncementsMethod from a JSON string
get_property_announcements_method_instance = GetPropertyAnnouncementsMethod.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAnnouncementsMethod.to_json())

# convert the object into a dict
get_property_announcements_method_dict = get_property_announcements_method_instance.to_dict()
# create an instance of GetPropertyAnnouncementsMethod from a dict
get_property_announcements_method_from_dict = GetPropertyAnnouncementsMethod.from_dict(get_property_announcements_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



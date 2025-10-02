# GetMarketingPreferencePickList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetMarketingPreferencePickListMethod**](GetMarketingPreferencePickListMethod.md) |  | 

## Example

```python
from openapi_client.models.get_marketing_preference_pick_list import GetMarketingPreferencePickList

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencePickList from a JSON string
get_marketing_preference_pick_list_instance = GetMarketingPreferencePickList.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencePickList.to_json())

# convert the object into a dict
get_marketing_preference_pick_list_dict = get_marketing_preference_pick_list_instance.to_dict()
# create an instance of GetMarketingPreferencePickList from a dict
get_marketing_preference_pick_list_from_dict = GetMarketingPreferencePickList.from_dict(get_marketing_preference_pick_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



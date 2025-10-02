# GetMarketingPreferences


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetMarketingPreferencesMethod**](GetMarketingPreferencesMethod.md) |  | 

## Example

```python
from openapi_client.models.get_marketing_preferences import GetMarketingPreferences

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferences from a JSON string
get_marketing_preferences_instance = GetMarketingPreferences.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferences.to_json())

# convert the object into a dict
get_marketing_preferences_dict = get_marketing_preferences_instance.to_dict()
# create an instance of GetMarketingPreferences from a dict
get_marketing_preferences_from_dict = GetMarketingPreferences.from_dict(get_marketing_preferences_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



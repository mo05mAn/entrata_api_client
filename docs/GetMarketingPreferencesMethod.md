# GetMarketingPreferencesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetMarketingPreferencesMethodParams**](GetMarketingPreferencesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_marketing_preferences_method import GetMarketingPreferencesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencesMethod from a JSON string
get_marketing_preferences_method_instance = GetMarketingPreferencesMethod.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencesMethod.to_json())

# convert the object into a dict
get_marketing_preferences_method_dict = get_marketing_preferences_method_instance.to_dict()
# create an instance of GetMarketingPreferencesMethod from a dict
get_marketing_preferences_method_from_dict = GetMarketingPreferencesMethod.from_dict(get_marketing_preferences_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



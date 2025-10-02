# GetMarketingPreferencesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**customer_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. Customer Ids | 
**recipient_type_id** | **int** | This is a required field. This field accepts single value. Possible values are 1 &#x3D; Lead 2 &#x3D; Resident | [optional] 

## Example

```python
from entrata_api_client.models.get_marketing_preferences_method_params import GetMarketingPreferencesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencesMethodParams from a JSON string
get_marketing_preferences_method_params_instance = GetMarketingPreferencesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencesMethodParams.to_json())

# convert the object into a dict
get_marketing_preferences_method_params_dict = get_marketing_preferences_method_params_instance.to_dict()
# create an instance of GetMarketingPreferencesMethodParams from a dict
get_marketing_preferences_method_params_from_dict = GetMarketingPreferencesMethodParams.from_dict(get_marketing_preferences_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



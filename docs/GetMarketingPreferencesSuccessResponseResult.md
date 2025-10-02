# GetMarketingPreferencesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customers** | [**List[GetMarketingPreferencesSuccessResponseResultCustomersInner]**](GetMarketingPreferencesSuccessResponseResultCustomersInner.md) |  | 

## Example

```python
from openapi_client.models.get_marketing_preferences_success_response_result import GetMarketingPreferencesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencesSuccessResponseResult from a JSON string
get_marketing_preferences_success_response_result_instance = GetMarketingPreferencesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencesSuccessResponseResult.to_json())

# convert the object into a dict
get_marketing_preferences_success_response_result_dict = get_marketing_preferences_success_response_result_instance.to_dict()
# create an instance of GetMarketingPreferencesSuccessResponseResult from a dict
get_marketing_preferences_success_response_result_from_dict = GetMarketingPreferencesSuccessResponseResult.from_dict(get_marketing_preferences_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetMarketingPreferencePickListSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**preferences** | [**List[GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner]**](GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner.md) |  | 
**availability_alert_frequencies** | [**List[GetMarketingPreferencePickListSuccessResponseResponseResultAvailabilityAlertFrequenciesInner]**](GetMarketingPreferencePickListSuccessResponseResponseResultAvailabilityAlertFrequenciesInner.md) |  | 

## Example

```python
from openapi_client.models.get_marketing_preference_pick_list_success_response_response_result import GetMarketingPreferencePickListSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencePickListSuccessResponseResponseResult from a JSON string
get_marketing_preference_pick_list_success_response_response_result_instance = GetMarketingPreferencePickListSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencePickListSuccessResponseResponseResult.to_json())

# convert the object into a dict
get_marketing_preference_pick_list_success_response_response_result_dict = get_marketing_preference_pick_list_success_response_response_result_instance.to_dict()
# create an instance of GetMarketingPreferencePickListSuccessResponseResponseResult from a dict
get_marketing_preference_pick_list_success_response_response_result_from_dict = GetMarketingPreferencePickListSuccessResponseResponseResult.from_dict(get_marketing_preference_pick_list_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**communication_channel** | **str** | The communication channel used for notifications | 
**recipient_type** | **str** | The type of recipient (e.g., LEAD, RESIDENT) | 
**recipient_type_id** | **int** | The identifier for the recipient type | 
**consent_type** | **str** | The type of consent for the communication | 
**consent_type_id** | **int** | The identifier for the consent type | 

## Example

```python
from openapi_client.models.get_marketing_preference_pick_list_success_response_response_result_preferences_inner import GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner from a JSON string
get_marketing_preference_pick_list_success_response_response_result_preferences_inner_instance = GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner.to_json())

# convert the object into a dict
get_marketing_preference_pick_list_success_response_response_result_preferences_inner_dict = get_marketing_preference_pick_list_success_response_response_result_preferences_inner_instance.to_dict()
# create an instance of GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner from a dict
get_marketing_preference_pick_list_success_response_response_result_preferences_inner_from_dict = GetMarketingPreferencePickListSuccessResponseResponseResultPreferencesInner.from_dict(get_marketing_preference_pick_list_success_response_response_result_preferences_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



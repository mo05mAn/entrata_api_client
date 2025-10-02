# GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**communication_channel** | **str** | The communication channel used for notifications | 
**recipient_type** | **str** | The type of recipient (e.g., LEAD, RESIDENT) | 
**recipient_type_id** | **str** | The identifier for the recipient type | 
**consent_type** | **str** | The type of consent for the communication | 
**consent_type_id** | **int** | The identifier for the consent type | 
**opt_in** | **str** | Opt-in status for the communication (1 for opted-in, 0 for opted-out) | 

## Example

```python
from openapi_client.models.get_marketing_preferences_success_response_result_customers_inner_preferences_inner import GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner from a JSON string
get_marketing_preferences_success_response_result_customers_inner_preferences_inner_instance = GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner.to_json())

# convert the object into a dict
get_marketing_preferences_success_response_result_customers_inner_preferences_inner_dict = get_marketing_preferences_success_response_result_customers_inner_preferences_inner_instance.to_dict()
# create an instance of GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner from a dict
get_marketing_preferences_success_response_result_customers_inner_preferences_inner_from_dict = GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner.from_dict(get_marketing_preferences_success_response_result_customers_inner_preferences_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



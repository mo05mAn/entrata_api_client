# GetMarketingPreferencesSuccessResponseResultCustomersInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **int** | The unique identifier for the customer | 
**preferences** | [**List[GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner]**](GetMarketingPreferencesSuccessResponseResultCustomersInnerPreferencesInner.md) |  | 

## Example

```python
from entrata_api_client.models.get_marketing_preferences_success_response_result_customers_inner import GetMarketingPreferencesSuccessResponseResultCustomersInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencesSuccessResponseResultCustomersInner from a JSON string
get_marketing_preferences_success_response_result_customers_inner_instance = GetMarketingPreferencesSuccessResponseResultCustomersInner.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencesSuccessResponseResultCustomersInner.to_json())

# convert the object into a dict
get_marketing_preferences_success_response_result_customers_inner_dict = get_marketing_preferences_success_response_result_customers_inner_instance.to_dict()
# create an instance of GetMarketingPreferencesSuccessResponseResultCustomersInner from a dict
get_marketing_preferences_success_response_result_customers_inner_from_dict = GetMarketingPreferencesSuccessResponseResultCustomersInner.from_dict(get_marketing_preferences_success_response_result_customers_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



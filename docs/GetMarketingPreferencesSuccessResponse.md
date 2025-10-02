# GetMarketingPreferencesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**code** | **int** | Response code indicating the status of the request | 
**result** | [**GetMarketingPreferencesSuccessResponseResult**](GetMarketingPreferencesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_marketing_preferences_success_response import GetMarketingPreferencesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencesSuccessResponse from a JSON string
get_marketing_preferences_success_response_instance = GetMarketingPreferencesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencesSuccessResponse.to_json())

# convert the object into a dict
get_marketing_preferences_success_response_dict = get_marketing_preferences_success_response_instance.to_dict()
# create an instance of GetMarketingPreferencesSuccessResponse from a dict
get_marketing_preferences_success_response_from_dict = GetMarketingPreferencesSuccessResponse.from_dict(get_marketing_preferences_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



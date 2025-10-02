# GetMarketingPreferencePickListSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**code** | **int** | Successful response code | 
**result** | [**GetMarketingPreferencePickListSuccessResponseResponseResult**](GetMarketingPreferencePickListSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_marketing_preference_pick_list_success_response_response import GetMarketingPreferencePickListSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetMarketingPreferencePickListSuccessResponseResponse from a JSON string
get_marketing_preference_pick_list_success_response_response_instance = GetMarketingPreferencePickListSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetMarketingPreferencePickListSuccessResponseResponse.to_json())

# convert the object into a dict
get_marketing_preference_pick_list_success_response_response_dict = get_marketing_preference_pick_list_success_response_response_instance.to_dict()
# create an instance of GetMarketingPreferencePickListSuccessResponseResponse from a dict
get_marketing_preference_pick_list_success_response_response_from_dict = GetMarketingPreferencePickListSuccessResponseResponse.from_dict(get_marketing_preference_pick_list_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetPropertyPickListsR2SuccessResponseResult

Contains properties, search areas, and other relevant data

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**properties** | [**GetPropertyPickListsR2SuccessResponseResultProperties**](GetPropertyPickListsR2SuccessResponseResultProperties.md) |  | 
**search_area_states** | [**GetPropertyPickListsR2SuccessResponseResultSearchAreaStates**](GetPropertyPickListsR2SuccessResponseResultSearchAreaStates.md) |  | 

## Example

```python
from openapi_client.models.get_property_pick_lists_r2_success_response_result import GetPropertyPickListsR2SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR2SuccessResponseResult from a JSON string
get_property_pick_lists_r2_success_response_result_instance = GetPropertyPickListsR2SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR2SuccessResponseResult.to_json())

# convert the object into a dict
get_property_pick_lists_r2_success_response_result_dict = get_property_pick_lists_r2_success_response_result_instance.to_dict()
# create an instance of GetPropertyPickListsR2SuccessResponseResult from a dict
get_property_pick_lists_r2_success_response_result_from_dict = GetPropertyPickListsR2SuccessResponseResult.from_dict(get_property_pick_lists_r2_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



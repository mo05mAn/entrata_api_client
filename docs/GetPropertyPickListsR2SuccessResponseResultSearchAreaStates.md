# GetPropertyPickListsR2SuccessResponseResultSearchAreaStates

Search area states and associated details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**search_area_state** | [**List[GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner]**](GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_pick_lists_r2_success_response_result_search_area_states import GetPropertyPickListsR2SuccessResponseResultSearchAreaStates

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR2SuccessResponseResultSearchAreaStates from a JSON string
get_property_pick_lists_r2_success_response_result_search_area_states_instance = GetPropertyPickListsR2SuccessResponseResultSearchAreaStates.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR2SuccessResponseResultSearchAreaStates.to_json())

# convert the object into a dict
get_property_pick_lists_r2_success_response_result_search_area_states_dict = get_property_pick_lists_r2_success_response_result_search_area_states_instance.to_dict()
# create an instance of GetPropertyPickListsR2SuccessResponseResultSearchAreaStates from a dict
get_property_pick_lists_r2_success_response_result_search_area_states_from_dict = GetPropertyPickListsR2SuccessResponseResultSearchAreaStates.from_dict(get_property_pick_lists_r2_success_response_result_search_area_states_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



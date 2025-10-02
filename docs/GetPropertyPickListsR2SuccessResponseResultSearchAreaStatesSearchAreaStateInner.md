# GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**state** | **str** | State name | 
**state_code** | **str** | State code | 
**country_code** | **str** | Country code | 
**search_areas** | [**GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInnerSearchAreas**](GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInnerSearchAreas.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_pick_lists_r2_success_response_result_search_area_states_search_area_state_inner import GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner from a JSON string
get_property_pick_lists_r2_success_response_result_search_area_states_search_area_state_inner_instance = GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner.to_json())

# convert the object into a dict
get_property_pick_lists_r2_success_response_result_search_area_states_search_area_state_inner_dict = get_property_pick_lists_r2_success_response_result_search_area_states_search_area_state_inner_instance.to_dict()
# create an instance of GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner from a dict
get_property_pick_lists_r2_success_response_result_search_area_states_search_area_state_inner_from_dict = GetPropertyPickListsR2SuccessResponseResultSearchAreaStatesSearchAreaStateInner.from_dict(get_property_pick_lists_r2_success_response_result_search_area_states_search_area_state_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



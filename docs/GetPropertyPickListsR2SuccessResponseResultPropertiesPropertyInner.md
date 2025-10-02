# GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Property ID | 
**name** | **str** | Property name | 
**unit_types** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerUnitTypes**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerUnitTypes.md) |  | 
**property_buildings** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerPropertyBuildings**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerPropertyBuildings.md) |  | 
**property_floorplans** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerPropertyFloorplans**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerPropertyFloorplans.md) |  | 
**property_floors** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerPropertyFloors**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerPropertyFloors.md) |  | 
**rentable_items** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerRentableItems**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerRentableItems.md) |  | 
**add_on_categories** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerAddOnCategories**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerAddOnCategories.md) |  | 
**assignable_items** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerAssignableItems**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerAssignableItems.md) |  | 
**services** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerServices**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerServices.md) |  | 
**move_out_types** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerMoveOutTypes**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerMoveOutTypes.md) |  | 
**move_out_reasons** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerMoveOutReasons**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerMoveOutReasons.md) |  | 
**lease_terms** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerLeaseTerms**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerLeaseTerms.md) |  | 
**unit_exclusion_reason_types** | [**GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerUnitExclusionReasonTypes**](GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInnerUnitExclusionReasonTypes.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_pick_lists_r2_success_response_result_properties_property_inner import GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInner from a JSON string
get_property_pick_lists_r2_success_response_result_properties_property_inner_instance = GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInner.from_json(json)
# print the JSON string representation of the object
print(GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInner.to_json())

# convert the object into a dict
get_property_pick_lists_r2_success_response_result_properties_property_inner_dict = get_property_pick_lists_r2_success_response_result_properties_property_inner_instance.to_dict()
# create an instance of GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInner from a dict
get_property_pick_lists_r2_success_response_result_properties_property_inner_from_dict = GetPropertyPickListsR2SuccessResponseResultPropertiesPropertyInner.from_dict(get_property_pick_lists_r2_success_response_result_properties_property_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



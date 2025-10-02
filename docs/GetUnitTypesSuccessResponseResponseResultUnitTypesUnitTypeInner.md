# GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification_type** | [**GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerIdentificationType**](GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerIdentificationType.md) |  | 
**name** | **str** | Name of the unit type | 
**floorplan** | [**Dict[str, GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerFloorplanValue]**](GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerFloorplanValue.md) | Floor plans available for this unit type | 
**unit_bed_rooms** | **str** | Number of bedrooms in the unit | 
**unit_bathrooms** | **str** | Number of bathrooms in the unit | 
**min_square_feet** | **str** | Minimum square footage of the unit | 
**max_square_feet** | **str** | Maximum square footage of the unit | 
**min_market_rent** | **str** | Minimum market rent for the unit | [optional] 
**max_market_rent** | **str** | Maximum market rent for the unit | [optional] 
**rent** | [**GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRent**](GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRent.md) |  | 

## Example

```python
from entrata_api_client.models.get_unit_types_success_response_response_result_unit_types_unit_type_inner import GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInner from a JSON string
get_unit_types_success_response_response_result_unit_types_unit_type_inner_instance = GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInner.from_json(json)
# print the JSON string representation of the object
print(GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInner.to_json())

# convert the object into a dict
get_unit_types_success_response_response_result_unit_types_unit_type_inner_dict = get_unit_types_success_response_response_result_unit_types_unit_type_inner_instance.to_dict()
# create an instance of GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInner from a dict
get_unit_types_success_response_response_result_unit_types_unit_type_inner_from_dict = GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInner.from_dict(get_unit_types_success_response_response_result_unit_types_unit_type_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



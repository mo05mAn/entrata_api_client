# GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpace


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**unit_space_id** | **int** | Unit space ID | 
**unit_number** | **str** | Unit space number | 
**is_affordable** | **int** | Indicates if the unit space is affordable | 
**has_pricing** | **int** | Indicates if the unit space has pricing | 
**excluded_reason** | **str** | Reason for exclusion from availability | 
**space_configuration** | **str** | Configuration of the space | 
**availability_status** | **str** | Availability status of the unit space | 
**available_date** | **str** | Date when the unit space will be available | 
**make_ready_date** | **str** | Date when the unit space will be ready | 
**rent** | [**GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpaceRent**](GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpaceRent.md) |  | 
**min_deposit** | **str** | Minimum deposit for the unit space | 
**max_deposit** | **str** | Maximum deposit for the unit space | 
**reserve_until** | **str** | Date until when the unit is reserved | 
**amenities** | [**GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpaceAmenities**](GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpaceAmenities.md) |  | 
**pets** | [**GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePets**](GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePets.md) |  | 

## Example

```python
from openapi_client.models.get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space import GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpace

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpace from a JSON string
get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_instance = GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpace.from_json(json)
# print the JSON string representation of the object
print(GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpace.to_json())

# convert the object into a dict
get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_dict = get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_instance.to_dict()
# create an instance of GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpace from a dict
get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_from_dict = GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpace.from_dict(get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



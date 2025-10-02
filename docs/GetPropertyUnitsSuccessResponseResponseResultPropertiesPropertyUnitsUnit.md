# GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnit


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unit ID | 
**unit_number** | **int** | Unit number | 
**building_id** | **int** | Building ID | 
**building_name** | **str** | Name of the building | 
**floorplan_id** | **int** | Floorplan ID | 
**floorplan_name** | **str** | Floorplan name | 
**unit_type_id** | **int** | Unit type ID | 
**unit_type_name** | **str** | Unit type name | 
**no_of_bedrooms** | **int** | Number of bedrooms in the unit | 
**no_of_bathrooms** | **int** | Number of bathrooms in the unit | 
**square_feet** | **int** | Unit size in square feet | 
**is_furnished** | **int** | Indicates if the unit is furnished | 
**is_corportate_rented** | **int** | Indicates if the unit is corporate rented | 
**number_occupants** | **int** | Number of occupants allowed in the unit | 
**max_pets** | **int** | Maximum number of pets allowed in the unit | 
**unit_availability_url** | **str** | URL for unit availability | 
**unit_address** | [**GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitAddress**](GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitAddress.md) |  | 
**unit_spaces** | [**GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpaces**](GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpaces.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_units_success_response_response_result_properties_property_units_unit import GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnit

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnit from a JSON string
get_property_units_success_response_response_result_properties_property_units_unit_instance = GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnit.from_json(json)
# print the JSON string representation of the object
print(GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnit.to_json())

# convert the object into a dict
get_property_units_success_response_response_result_properties_property_units_unit_dict = get_property_units_success_response_response_result_properties_property_units_unit_instance.to_dict()
# create an instance of GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnit from a dict
get_property_units_success_response_response_result_properties_property_units_unit_from_dict = GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnit.from_dict(get_property_units_success_response_response_result_properties_property_units_unit_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



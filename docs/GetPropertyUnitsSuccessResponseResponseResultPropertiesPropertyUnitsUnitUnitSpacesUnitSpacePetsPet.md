# GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePetsPet


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Pet type | 
**count** | **int** | Number of pets allowed | 
**deposit** | **int** | Deposit for the pet | 
**rent** | **int** | Rent for the pet | 
**fee** | **int** | Fee for the pet | 
**pet_care** | **bool** | Indicates if pet care is provided | 
**restrictions** | **str** | Pet restrictions | 
**description** | **str** | Description of pet policy | 

## Example

```python
from entrata_api_client.models.get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_pets_pet import GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePetsPet

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePetsPet from a JSON string
get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_pets_pet_instance = GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePetsPet.from_json(json)
# print the JSON string representation of the object
print(GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePetsPet.to_json())

# convert the object into a dict
get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_pets_pet_dict = get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_pets_pet_instance.to_dict()
# create an instance of GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePetsPet from a dict
get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_pets_pet_from_dict = GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnitsUnitUnitSpacesUnitSpacePetsPet.from_dict(get_property_units_success_response_response_result_properties_property_units_unit_unit_spaces_unit_space_pets_pet_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInnerPetsAttributes

Attributes related to the pet policy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**count** | **str** | Number of pets allowed | [optional] 
**description** | **str** | Description of the pets allowed | [optional] 
**pet_type** | **str** | Type of pet allowed | [optional] 
**size** | **str** | Size of the pet | [optional] 
**weight** | **str** | Weight of the pet | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result_physical_property_policy_pet_inner_pets_attributes import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInnerPetsAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInnerPetsAttributes from a JSON string
get_mits_property_units_success_response_result_physical_property_policy_pet_inner_pets_attributes_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInnerPetsAttributes.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInnerPetsAttributes.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_policy_pet_inner_pets_attributes_dict = get_mits_property_units_success_response_result_physical_property_policy_pet_inner_pets_attributes_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInnerPetsAttributes from a dict
get_mits_property_units_success_response_result_physical_property_policy_pet_inner_pets_attributes_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicyPetInnerPetsAttributes.from_dict(get_mits_property_units_success_response_result_physical_property_policy_pet_inner_pets_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the unit type. | 
**name** | **str** | The name of the unit type. | 
**rates** | [**List[GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitTypeRatesInner]**](GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitTypeRatesInner.md) | List of rates associated with the unit type. | 
**lease_terms** | [**List[GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialLeaseTermsInner]**](GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialLeaseTermsInner.md) | List of lease terms for the unit type. | 

## Example

```python
from entrata_api_client.models.get_specials_r2_success_response_specials_unit_type_specials_special_unit_types_unit_type import GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitType

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitType from a JSON string
get_specials_r2_success_response_specials_unit_type_specials_special_unit_types_unit_type_instance = GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitType.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitType.to_json())

# convert the object into a dict
get_specials_r2_success_response_specials_unit_type_specials_special_unit_types_unit_type_dict = get_specials_r2_success_response_specials_unit_type_specials_special_unit_types_unit_type_instance.to_dict()
# create an instance of GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitType from a dict
get_specials_r2_success_response_specials_unit_type_specials_special_unit_types_unit_type_from_dict = GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecialsSpecialUnitTypesUnitType.from_dict(get_specials_r2_success_response_specials_unit_type_specials_special_unit_types_unit_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



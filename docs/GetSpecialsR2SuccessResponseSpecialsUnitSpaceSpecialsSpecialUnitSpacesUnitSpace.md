# GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpace


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the unit space. | 
**building_id** | **str** | The building ID for the unit space. | 
**building_name** | **str** | The name of the building. | 
**property_unit_id** | **str** | The property unit ID for the unit space. | 
**name** | **str** | The name of the unit space. | 
**rates** | [**List[GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpaceRatesInner]**](GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpaceRatesInner.md) | List of rates associated with the unit space. | 
**lease_terms** | [**List[GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialLeaseTermsInner]**](GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialLeaseTermsInner.md) | List of lease terms for the unit space. | 

## Example

```python
from openapi_client.models.get_specials_r2_success_response_specials_unit_space_specials_special_unit_spaces_unit_space import GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpace

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpace from a JSON string
get_specials_r2_success_response_specials_unit_space_specials_special_unit_spaces_unit_space_instance = GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpace.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpace.to_json())

# convert the object into a dict
get_specials_r2_success_response_specials_unit_space_specials_special_unit_spaces_unit_space_dict = get_specials_r2_success_response_specials_unit_space_specials_special_unit_spaces_unit_space_instance.to_dict()
# create an instance of GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpace from a dict
get_specials_r2_success_response_specials_unit_space_specials_special_unit_spaces_unit_space_from_dict = GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpacesUnitSpace.from_dict(get_specials_r2_success_response_specials_unit_space_specials_special_unit_spaces_unit_space_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



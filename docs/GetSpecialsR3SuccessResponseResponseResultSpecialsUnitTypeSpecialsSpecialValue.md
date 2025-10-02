# GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique ID for the unit type special. | 
**name** | **str** | The name of the special. | 
**show_on_website** | **int** | Indicates if the special is shown on the website. | 
**is_active** | **int** | Indicates if the special is active. | 
**gift_value** | **str** | The value of the gift associated with the special. | 
**unit_types** | [**GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValueUnitTypes**](GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValueUnitTypes.md) |  | 

## Example

```python
from openapi_client.models.get_specials_r3_success_response_response_result_specials_unit_type_specials_special_value import GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValue

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValue from a JSON string
get_specials_r3_success_response_response_result_specials_unit_type_specials_special_value_instance = GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValue.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValue.to_json())

# convert the object into a dict
get_specials_r3_success_response_response_result_specials_unit_type_specials_special_value_dict = get_specials_r3_success_response_response_result_specials_unit_type_specials_special_value_instance.to_dict()
# create an instance of GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValue from a dict
get_specials_r3_success_response_response_result_specials_unit_type_specials_special_value_from_dict = GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecialsSpecialValue.from_dict(get_specials_r3_success_response_response_result_specials_unit_type_specials_special_value_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



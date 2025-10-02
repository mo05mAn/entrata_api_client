# GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique ID for the special. | 
**name** | **str** | The name of the special. | 
**description** | **str** | Description of the special. | 
**start_date** | **date** | The start date of the special. | 
**end_date** | **date** | The end date of the special. | 
**coupon_code** | **str** | Coupon code for the special. | 
**cap** | **str** | The cap limit for the special. | 
**remaining** | **str** | The remaining quantity of the special. | 
**show_on_website** | **str** | Flag to indicate if the special should be shown on the website. | 
**is_active** | **str** | Flag to indicate if the special is active. | 
**unit_spaces** | [**GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpaces**](GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecialUnitSpaces.md) |  | 

## Example

```python
from openapi_client.models.get_specials_r2_success_response_specials_unit_space_specials_special import GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecial

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecial from a JSON string
get_specials_r2_success_response_specials_unit_space_specials_special_instance = GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecial.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecial.to_json())

# convert the object into a dict
get_specials_r2_success_response_specials_unit_space_specials_special_dict = get_specials_r2_success_response_specials_unit_space_specials_special_instance.to_dict()
# create an instance of GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecial from a dict
get_specials_r2_success_response_specials_unit_space_specials_special_from_dict = GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecialsSpecial.from_dict(get_specials_r2_success_response_specials_unit_space_specials_special_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetSpecialsR2SuccessResponseSpecials


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | The unique identifier for the property. | 
**organization_name** | **str** | The name of the organization associated with the property. | 
**marketing_name** | **str** | The marketing name of the property. | 
**legal_name** | **str** | The legal name of the property. | 
**property_specials** | [**GetSpecialsR2SuccessResponseSpecialsPropertySpecials**](GetSpecialsR2SuccessResponseSpecialsPropertySpecials.md) |  | 
**floorplan_specials** | [**GetSpecialsR2SuccessResponseSpecialsFloorplanSpecials**](GetSpecialsR2SuccessResponseSpecialsFloorplanSpecials.md) |  | 
**unit_type_specials** | [**GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecials**](GetSpecialsR2SuccessResponseSpecialsUnitTypeSpecials.md) |  | 
**unit_space_specials** | [**GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecials**](GetSpecialsR2SuccessResponseSpecialsUnitSpaceSpecials.md) |  | 

## Example

```python
from entrata_api_client.models.get_specials_r2_success_response_specials import GetSpecialsR2SuccessResponseSpecials

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2SuccessResponseSpecials from a JSON string
get_specials_r2_success_response_specials_instance = GetSpecialsR2SuccessResponseSpecials.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2SuccessResponseSpecials.to_json())

# convert the object into a dict
get_specials_r2_success_response_specials_dict = get_specials_r2_success_response_specials_instance.to_dict()
# create an instance of GetSpecialsR2SuccessResponseSpecials from a dict
get_specials_r2_success_response_specials_from_dict = GetSpecialsR2SuccessResponseSpecials.from_dict(get_specials_r2_success_response_specials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetSpecialsR3SuccessResponseResponseResultSpecials


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | The unique identifier for the property. | 
**organization_name** | **str** | The name of the organization associated with the property. | 
**marketing_name** | **str** | The marketing name of the property. | 
**legal_name** | **str** | The legal name of the property. | 
**property_specials** | [**GetSpecialsR3SuccessResponseResponseResultSpecialsPropertySpecials**](GetSpecialsR3SuccessResponseResponseResultSpecialsPropertySpecials.md) |  | 
**floorplan_specials** | [**GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecials**](GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecials.md) |  | 
**unit_type_specials** | [**GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecials**](GetSpecialsR3SuccessResponseResponseResultSpecialsUnitTypeSpecials.md) |  | 
**unit_space_specials** | [**GetSpecialsR3SuccessResponseResponseResultSpecialsUnitSpaceSpecials**](GetSpecialsR3SuccessResponseResponseResultSpecialsUnitSpaceSpecials.md) |  | 

## Example

```python
from entrata_api_client.models.get_specials_r3_success_response_response_result_specials import GetSpecialsR3SuccessResponseResponseResultSpecials

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR3SuccessResponseResponseResultSpecials from a JSON string
get_specials_r3_success_response_response_result_specials_instance = GetSpecialsR3SuccessResponseResponseResultSpecials.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR3SuccessResponseResponseResultSpecials.to_json())

# convert the object into a dict
get_specials_r3_success_response_response_result_specials_dict = get_specials_r3_success_response_response_result_specials_instance.to_dict()
# create an instance of GetSpecialsR3SuccessResponseResponseResultSpecials from a dict
get_specials_r3_success_response_response_result_specials_from_dict = GetSpecialsR3SuccessResponseResponseResultSpecials.from_dict(get_specials_r3_success_response_response_result_specials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



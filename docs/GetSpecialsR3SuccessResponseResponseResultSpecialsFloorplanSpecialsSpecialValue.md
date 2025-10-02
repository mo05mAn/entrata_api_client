# GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique ID for the floorplan special. | 
**name** | **str** | The name of the special. | 
**description** | **str** | Description of the special. | 
**start_date** | **date** | The start date of the special. | 
**end_date** | **date** | The end date of the special. | 
**show_on_website** | **int** | Indicates if the special is shown on the website. | 
**is_active** | **int** | Indicates if the special is active. | 
**gift_value** | **str** | The value of the gift associated with the special. | 
**floorplans** | [**GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValueFloorplans**](GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValueFloorplans.md) |  | 

## Example

```python
from entrata_api_client.models.get_specials_r3_success_response_response_result_specials_floorplan_specials_special_value import GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValue

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValue from a JSON string
get_specials_r3_success_response_response_result_specials_floorplan_specials_special_value_instance = GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValue.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValue.to_json())

# convert the object into a dict
get_specials_r3_success_response_response_result_specials_floorplan_specials_special_value_dict = get_specials_r3_success_response_response_result_specials_floorplan_specials_special_value_instance.to_dict()
# create an instance of GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValue from a dict
get_specials_r3_success_response_response_result_specials_floorplan_specials_special_value_from_dict = GetSpecialsR3SuccessResponseResponseResultSpecialsFloorplanSpecialsSpecialValue.from_dict(get_specials_r3_success_response_response_result_specials_floorplan_specials_special_value_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



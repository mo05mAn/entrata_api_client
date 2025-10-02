# GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecial


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
**floorplans** | [**GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplans**](GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplans.md) |  | 

## Example

```python
from entrata_api_client.models.get_specials_r2_success_response_specials_floorplan_specials_special import GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecial

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecial from a JSON string
get_specials_r2_success_response_specials_floorplan_specials_special_instance = GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecial.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecial.to_json())

# convert the object into a dict
get_specials_r2_success_response_specials_floorplan_specials_special_dict = get_specials_r2_success_response_specials_floorplan_specials_special_instance.to_dict()
# create an instance of GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecial from a dict
get_specials_r2_success_response_specials_floorplan_specials_special_from_dict = GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecial.from_dict(get_specials_r2_success_response_specials_floorplan_specials_special_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



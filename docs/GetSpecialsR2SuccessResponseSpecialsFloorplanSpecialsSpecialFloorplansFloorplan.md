# GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplan


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the floorplan. | 
**name** | **str** | The name of the floorplan. | 
**rates** | [**List[GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplanRatesInner]**](GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplanRatesInner.md) | List of rates associated with the floorplan. | 
**lease_terms** | [**List[GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialLeaseTermsInner]**](GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialLeaseTermsInner.md) | List of lease terms for the floorplan. | 

## Example

```python
from entrata_api_client.models.get_specials_r2_success_response_specials_floorplan_specials_special_floorplans_floorplan import GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplan

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplan from a JSON string
get_specials_r2_success_response_specials_floorplan_specials_special_floorplans_floorplan_instance = GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplan.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplan.to_json())

# convert the object into a dict
get_specials_r2_success_response_specials_floorplan_specials_special_floorplans_floorplan_dict = get_specials_r2_success_response_specials_floorplan_specials_special_floorplans_floorplan_instance.to_dict()
# create an instance of GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplan from a dict
get_specials_r2_success_response_specials_floorplan_specials_special_floorplans_floorplan_from_dict = GetSpecialsR2SuccessResponseSpecialsFloorplanSpecialsSpecialFloorplansFloorplan.from_dict(get_specials_r2_success_response_specials_floorplan_specials_special_floorplans_floorplan_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



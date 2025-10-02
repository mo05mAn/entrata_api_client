# GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInnerIdentification**](GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInnerIdentification.md) |  | 
**name** | **str** | The name of the floorplan. | 
**comment** | **str** | A comment about the floorplan. | 
**concession** | [**List[GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInnerConcessionInner]**](GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInnerConcessionInner.md) | List of concessions for the floorplan. | 

## Example

```python
from openapi_client.models.get_specials_r1_success_response_response_result_physical_property_property_floorplan_inner import GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner from a JSON string
get_specials_r1_success_response_response_result_physical_property_property_floorplan_inner_instance = GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner.to_json())

# convert the object into a dict
get_specials_r1_success_response_response_result_physical_property_property_floorplan_inner_dict = get_specials_r1_success_response_response_result_physical_property_property_floorplan_inner_instance.to_dict()
# create an instance of GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner from a dict
get_specials_r1_success_response_response_result_physical_property_property_floorplan_inner_from_dict = GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner.from_dict(get_specials_r1_success_response_response_result_physical_property_property_floorplan_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



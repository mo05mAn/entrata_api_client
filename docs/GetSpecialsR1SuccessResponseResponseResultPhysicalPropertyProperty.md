# GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyIdentification**](GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyIdentification.md) |  | 
**property_id** | [**GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyPropertyID**](GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyPropertyID.md) |  | 
**concession** | [**List[GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyConcessionInner]**](GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyConcessionInner.md) | List of concessions for the property. | 
**floorplan** | [**List[GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner]**](GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyFloorplanInner.md) | List of floorplans for the property. | 
**ils_unit** | [**List[GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyILSUnitInner]**](GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyPropertyILSUnitInner.md) | List of units associated with the property. | 

## Example

```python
from entrata_api_client.models.get_specials_r1_success_response_response_result_physical_property_property import GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyProperty from a JSON string
get_specials_r1_success_response_response_result_physical_property_property_instance = GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyProperty.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyProperty.to_json())

# convert the object into a dict
get_specials_r1_success_response_response_result_physical_property_property_dict = get_specials_r1_success_response_response_result_physical_property_property_instance.to_dict()
# create an instance of GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyProperty from a dict
get_specials_r1_success_response_response_result_physical_property_property_from_dict = GetSpecialsR1SuccessResponseResponseResultPhysicalPropertyProperty.from_dict(get_specials_r1_success_response_response_result_physical_property_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty

Physical property details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**management** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement.md) |  | [optional] 
**var_property** | [**List[GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInner]**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInner.md) | Details of the property | [optional] 
**fee** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyFee**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyFee.md) |  | [optional] 
**concession** | [**List[GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner]**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyConcessionInner.md) | Concession details for the property | [optional] 
**amenity** | [**List[GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyAmenityInner]**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyAmenityInner.md) | Property amenities | [optional] 
**policy** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPolicy.md) |  | [optional] 
**building** | [**List[GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner]**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner.md) | Details of the building | [optional] 

## Example

```python
from openapi_client.models.get_mits_property_units_success_response_result_physical_property import GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty from a JSON string
get_mits_property_units_success_response_result_physical_property_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_dict = get_mits_property_units_success_response_result_physical_property_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty from a dict
get_mits_property_units_success_response_result_physical_property_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalProperty.from_dict(get_mits_property_units_success_response_result_physical_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



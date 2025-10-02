# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformation

General information about the property

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**structure_type** | **str** | Type of the property structure | [optional] 
**unit_count** | **str** | Number of units in the property | [optional] 
**year_built** | **str** | Year the property was built | [optional] 
**office_hour** | [**List[GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformationOfficeHourInner]**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformationOfficeHourInner.md) | Office hours for the property | [optional] 
**short_description** | **str** | Short description of the property | [optional] 
**long_description** | **str** | Long description of the property | [optional] 
**lease_length** | **str** | Available lease lengths | [optional] 
**driving_directions** | **str** | Directions to the property | [optional] 
**property_availability_url** | **str** | URL for property availability | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result_physical_property_property_inner_information import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformation

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformation from a JSON string
get_mits_property_units_success_response_result_physical_property_property_inner_information_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformation.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformation.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_property_inner_information_dict = get_mits_property_units_success_response_result_physical_property_property_inner_information_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformation from a dict
get_mits_property_units_success_response_result_physical_property_property_inner_information_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerInformation.from_dict(get_mits_property_units_success_response_result_physical_property_property_inner_information_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



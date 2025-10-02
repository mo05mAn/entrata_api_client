# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInnerIdentification**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInnerIdentification.md) |  | [optional] 
**name** | **str** | Name of the building | [optional] 
**description** | **str** | Description of the building | [optional] 
**unit_count** | **str** | Number of units in the building | [optional] 
**square_feet** | **str** | Square footage of the building | [optional] 
**file** | [**List[GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInnerFileInner]**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInnerFileInner.md) | Files related to the building | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result_physical_property_building_inner import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner from a JSON string
get_mits_property_units_success_response_result_physical_property_building_inner_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_building_inner_dict = get_mits_property_units_success_response_result_physical_property_building_inner_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner from a dict
get_mits_property_units_success_response_result_physical_property_building_inner_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyBuildingInner.from_dict(get_mits_property_units_success_response_result_physical_property_building_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



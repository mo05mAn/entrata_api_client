# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification

Identification details for the management

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id_value** | **str** | Unique ID for the management | [optional] 
**organization_name** | **str** | Name of the managing organization | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result_physical_property_management_identification import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification from a JSON string
get_mits_property_units_success_response_result_physical_property_management_identification_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_management_identification_dict = get_mits_property_units_success_response_result_physical_property_management_identification_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification from a dict
get_mits_property_units_success_response_result_physical_property_management_identification_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification.from_dict(get_mits_property_units_success_response_result_physical_property_management_identification_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement

Property management information

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementIdentification.md) |  | [optional] 
**property_contacts** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContacts**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContacts.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result_physical_property_management import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement from a JSON string
get_mits_property_units_success_response_result_physical_property_management_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_management_dict = get_mits_property_units_success_response_result_physical_property_management_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement from a dict
get_mits_property_units_success_response_result_physical_property_management_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagement.from_dict(get_mits_property_units_success_response_result_physical_property_management_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



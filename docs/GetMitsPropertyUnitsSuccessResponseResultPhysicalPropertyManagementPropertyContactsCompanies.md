# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompanies

Companies related to the property

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompaniesIdentification**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompaniesIdentification.md) |  | [optional] 
**company_name** | **str** | Name of the company | [optional] 
**web_site** | **str** | Company website URL | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result_physical_property_management_property_contacts_companies import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompanies

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompanies from a JSON string
get_mits_property_units_success_response_result_physical_property_management_property_contacts_companies_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompanies.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompanies.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_management_property_contacts_companies_dict = get_mits_property_units_success_response_result_physical_property_management_property_contacts_companies_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompanies from a dict
get_mits_property_units_success_response_result_physical_property_management_property_contacts_companies_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyManagementPropertyContactsCompanies.from_dict(get_mits_property_units_success_response_result_physical_property_management_property_contacts_companies_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



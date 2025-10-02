# GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress

Address of the property

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | Street address | [optional] 
**city** | **str** | City of the property | [optional] 
**state** | **str** | State of the property | [optional] 
**postal_code** | **str** | Postal code of the property | [optional] 
**country** | **str** | Country of the property | [optional] 
**email** | **str** | Contact email for the property | [optional] 
**attributes** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddressAttributes**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddressAttributes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_properties_success_response_result_physical_property_property_inner_address import GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress from a JSON string
get_properties_success_response_result_physical_property_property_inner_address_instance = GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress.from_json(json)
# print the JSON string representation of the object
print(GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress.to_json())

# convert the object into a dict
get_properties_success_response_result_physical_property_property_inner_address_dict = get_properties_success_response_result_physical_property_property_inner_address_instance.to_dict()
# create an instance of GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress from a dict
get_properties_success_response_result_physical_property_property_inner_address_from_dict = GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress.from_dict(get_properties_success_response_result_physical_property_property_inner_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyID

Property ID and details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyIDIdentification**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyIDIdentification.md) |  | [optional] 
**marketing_name** | **str** | Marketing name of the property | [optional] 
**legal_name** | **str** | Legal name of the property | [optional] 
**web_site** | **str** | Property website | [optional] 
**address** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyIDAddress**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyIDAddress.md) |  | [optional] 
**phone** | [**List[GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyIDPhoneInner]**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyIDPhoneInner.md) | Phone numbers associated with the property | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_property_units_success_response_result_physical_property_property_inner_property_id import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyID

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyID from a JSON string
get_mits_property_units_success_response_result_physical_property_property_inner_property_id_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyID.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyID.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_property_inner_property_id_dict = get_mits_property_units_success_response_result_physical_property_property_inner_property_id_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyID from a dict
get_mits_property_units_success_response_result_physical_property_property_inner_property_id_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerPropertyID.from_dict(get_mits_property_units_success_response_result_physical_property_property_inner_property_id_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



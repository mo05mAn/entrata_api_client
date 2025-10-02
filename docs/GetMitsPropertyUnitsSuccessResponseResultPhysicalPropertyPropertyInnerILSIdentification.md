# GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentification

ILS identification details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**daylight_saving** | **str** | Daylight saving time status | [optional] 
**time_zone** | **str** | Time zone of the property | [optional] 
**attributes** | [**GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentificationAttributes**](GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentificationAttributes.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_mits_property_units_success_response_result_physical_property_property_inner_ils_identification import GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentification

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentification from a JSON string
get_mits_property_units_success_response_result_physical_property_property_inner_ils_identification_instance = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentification.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentification.to_json())

# convert the object into a dict
get_mits_property_units_success_response_result_physical_property_property_inner_ils_identification_dict = get_mits_property_units_success_response_result_physical_property_property_inner_ils_identification_instance.to_dict()
# create an instance of GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentification from a dict
get_mits_property_units_success_response_result_physical_property_property_inner_ils_identification_from_dict = GetMitsPropertyUnitsSuccessResponseResultPhysicalPropertyPropertyInnerILSIdentification.from_dict(get_mits_property_units_success_response_result_physical_property_property_inner_ils_identification_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



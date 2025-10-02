# GetPropertiesSuccessResponseResultPhysicalProperty

Physical property details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_property** | [**List[GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner]**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner.md) | List of properties | 

## Example

```python
from entrata_api_client.models.get_properties_success_response_result_physical_property import GetPropertiesSuccessResponseResultPhysicalProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertiesSuccessResponseResultPhysicalProperty from a JSON string
get_properties_success_response_result_physical_property_instance = GetPropertiesSuccessResponseResultPhysicalProperty.from_json(json)
# print the JSON string representation of the object
print(GetPropertiesSuccessResponseResultPhysicalProperty.to_json())

# convert the object into a dict
get_properties_success_response_result_physical_property_dict = get_properties_success_response_result_physical_property_instance.to_dict()
# create an instance of GetPropertiesSuccessResponseResultPhysicalProperty from a dict
get_properties_success_response_result_physical_property_from_dict = GetPropertiesSuccessResponseResultPhysicalProperty.from_dict(get_properties_success_response_result_physical_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



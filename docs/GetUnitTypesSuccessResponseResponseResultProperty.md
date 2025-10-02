# GetUnitTypesSuccessResponseResponseResultProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Type of the property | 
**property_id** | **str** | Unique identifier for the property | 
**parent_property_id** | **str** | Parent property identifier | [optional] 
**marketing_name** | **str** | Marketing name of the property | 
**general_id** | **str** | General identifier for the property | [optional] 
**year_built** | **str** | Year the property was built | [optional] 
**short_description** | **str** | Short description of the property | 
**long_description** | **str** | Long description of the property | 

## Example

```python
from entrata_api_client.models.get_unit_types_success_response_response_result_property import GetUnitTypesSuccessResponseResponseResultProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitTypesSuccessResponseResponseResultProperty from a JSON string
get_unit_types_success_response_response_result_property_instance = GetUnitTypesSuccessResponseResponseResultProperty.from_json(json)
# print the JSON string representation of the object
print(GetUnitTypesSuccessResponseResponseResultProperty.to_json())

# convert the object into a dict
get_unit_types_success_response_response_result_property_dict = get_unit_types_success_response_response_result_property_instance.to_dict()
# create an instance of GetUnitTypesSuccessResponseResponseResultProperty from a dict
get_unit_types_success_response_response_result_property_from_dict = GetUnitTypesSuccessResponseResponseResultProperty.from_dict(get_unit_types_success_response_response_result_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetUnitTypesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 

## Example

```python
from entrata_api_client.models.get_unit_types_method_params import GetUnitTypesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitTypesMethodParams from a JSON string
get_unit_types_method_params_instance = GetUnitTypesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetUnitTypesMethodParams.to_json())

# convert the object into a dict
get_unit_types_method_params_dict = get_unit_types_method_params_instance.to_dict()
# create an instance of GetUnitTypesMethodParams from a dict
get_unit_types_method_params_from_dict = GetUnitTypesMethodParams.from_dict(get_unit_types_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



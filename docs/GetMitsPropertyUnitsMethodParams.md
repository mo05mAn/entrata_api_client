# GetMitsPropertyUnitsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. PSI Property Identification number | 
**available_units_only** | **int** | This is an optional field. This field accepts single value. Flag for getting available units only | [optional] 
**use_property_preferences** | **int** | This is an optional field. This field accepts single value. Flag for implementing preferences on result. | [optional] 
**include_disabled_floorplans** | **int** | This is an optional field. This field accepts single value. Flag for implementing Disabled Floorplans on result. | [optional] 
**include_disabled_units** | **int** | This is an optional field. This field accepts single value. Flag for implementing Disabled Units on result. | [optional] 
**show_unit_spaces** | **int** | This is an optional field. This field accepts single value. Flag for implementing Unit Spaces on result. | [optional] 

## Example

```python
from openapi_client.models.get_mits_property_units_method_params import GetMitsPropertyUnitsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnitsMethodParams from a JSON string
get_mits_property_units_method_params_instance = GetMitsPropertyUnitsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnitsMethodParams.to_json())

# convert the object into a dict
get_mits_property_units_method_params_dict = get_mits_property_units_method_params_instance.to_dict()
# create an instance of GetMitsPropertyUnitsMethodParams from a dict
get_mits_property_units_method_params_from_dict = GetMitsPropertyUnitsMethodParams.from_dict(get_mits_property_units_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetPropertyUnitsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. | 
**available_units_only** | **int** | This is an optional field. This field accepts single value. | [optional] 
**use_property_preferences** | **int** | This is an optional field. This field accepts single value. If enabled then the Entrata setting \&quot;Max Available Units per Floor P lan\&quot; will be honored and the available units returned will be reduced. Also requires using the availableUnitsOnly parameter as true (1). | [optional] 
**include_disabled_floorplans** | **int** | This is an optional field. This field accepts single value. | [optional] 
**include_disabled_units** | **int** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.get_property_units_method_params import GetPropertyUnitsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyUnitsMethodParams from a JSON string
get_property_units_method_params_instance = GetPropertyUnitsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPropertyUnitsMethodParams.to_json())

# convert the object into a dict
get_property_units_method_params_dict = get_property_units_method_params_instance.to_dict()
# create an instance of GetPropertyUnitsMethodParams from a dict
get_property_units_method_params_from_dict = GetPropertyUnitsMethodParams.from_dict(get_property_units_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



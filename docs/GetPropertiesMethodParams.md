# GetPropertiesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. PropertyIds | [optional] 
**property_lookup_code** | **str** | This is an optional field. This field accepts single value. | [optional] 
**show_all_status** | **int** | This is an optional field. This field accepts single value. Show all properties with any status. | [optional] 

## Example

```python
from entrata_api_client.models.get_properties_method_params import GetPropertiesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertiesMethodParams from a JSON string
get_properties_method_params_instance = GetPropertiesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPropertiesMethodParams.to_json())

# convert the object into a dict
get_properties_method_params_dict = get_properties_method_params_instance.to_dict()
# create an instance of GetPropertiesMethodParams from a dict
get_properties_method_params_from_dict = GetPropertiesMethodParams.from_dict(get_properties_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



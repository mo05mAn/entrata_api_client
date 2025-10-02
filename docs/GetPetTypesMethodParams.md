# GetPetTypesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. List of comma seperated propertyIds | 

## Example

```python
from entrata_api_client.models.get_pet_types_method_params import GetPetTypesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPetTypesMethodParams from a JSON string
get_pet_types_method_params_instance = GetPetTypesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPetTypesMethodParams.to_json())

# convert the object into a dict
get_pet_types_method_params_dict = get_pet_types_method_params_instance.to_dict()
# create an instance of GetPetTypesMethodParams from a dict
get_pet_types_method_params_from_dict = GetPetTypesMethodParams.from_dict(get_pet_types_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



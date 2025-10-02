# GetPetTypesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPetTypesMethodParams**](GetPetTypesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_pet_types_method import GetPetTypesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetPetTypesMethod from a JSON string
get_pet_types_method_instance = GetPetTypesMethod.from_json(json)
# print the JSON string representation of the object
print(GetPetTypesMethod.to_json())

# convert the object into a dict
get_pet_types_method_dict = get_pet_types_method_instance.to_dict()
# create an instance of GetPetTypesMethod from a dict
get_pet_types_method_from_dict = GetPetTypesMethod.from_dict(get_pet_types_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



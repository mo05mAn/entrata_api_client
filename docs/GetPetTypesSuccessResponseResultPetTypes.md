# GetPetTypesSuccessResponseResultPetTypes

Pet types available for the properties

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_property** | [**Dict[str, GetPetTypesSuccessResponseResultPetTypesPropertyValue]**](GetPetTypesSuccessResponseResultPetTypesPropertyValue.md) | Properties containing pet type data | 

## Example

```python
from openapi_client.models.get_pet_types_success_response_result_pet_types import GetPetTypesSuccessResponseResultPetTypes

# TODO update the JSON string below
json = "{}"
# create an instance of GetPetTypesSuccessResponseResultPetTypes from a JSON string
get_pet_types_success_response_result_pet_types_instance = GetPetTypesSuccessResponseResultPetTypes.from_json(json)
# print the JSON string representation of the object
print(GetPetTypesSuccessResponseResultPetTypes.to_json())

# convert the object into a dict
get_pet_types_success_response_result_pet_types_dict = get_pet_types_success_response_result_pet_types_instance.to_dict()
# create an instance of GetPetTypesSuccessResponseResultPetTypes from a dict
get_pet_types_success_response_result_pet_types_from_dict = GetPetTypesSuccessResponseResultPetTypes.from_dict(get_pet_types_success_response_result_pet_types_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



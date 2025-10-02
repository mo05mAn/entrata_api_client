# GetPetTypesSuccessResponseResult

Result containing pet types for properties

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pet_types** | [**GetPetTypesSuccessResponseResultPetTypes**](GetPetTypesSuccessResponseResultPetTypes.md) |  | 

## Example

```python
from openapi_client.models.get_pet_types_success_response_result import GetPetTypesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPetTypesSuccessResponseResult from a JSON string
get_pet_types_success_response_result_instance = GetPetTypesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPetTypesSuccessResponseResult.to_json())

# convert the object into a dict
get_pet_types_success_response_result_dict = get_pet_types_success_response_result_instance.to_dict()
# create an instance of GetPetTypesSuccessResponseResult from a dict
get_pet_types_success_response_result_from_dict = GetPetTypesSuccessResponseResult.from_dict(get_pet_types_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



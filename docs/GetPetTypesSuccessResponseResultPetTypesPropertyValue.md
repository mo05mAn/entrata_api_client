# GetPetTypesSuccessResponseResultPetTypesPropertyValue

Specific pet types for each property

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | [**GetPetTypesSuccessResponseResultPetTypesPropertyValueAttributes**](GetPetTypesSuccessResponseResultPetTypesPropertyValueAttributes.md) |  | [optional] 
**pet_type** | [**List[GetPetTypesSuccessResponseResultPetTypesPropertyValuePetTypeInner]**](GetPetTypesSuccessResponseResultPetTypesPropertyValuePetTypeInner.md) | List of pet types available for the property | [optional] 

## Example

```python
from openapi_client.models.get_pet_types_success_response_result_pet_types_property_value import GetPetTypesSuccessResponseResultPetTypesPropertyValue

# TODO update the JSON string below
json = "{}"
# create an instance of GetPetTypesSuccessResponseResultPetTypesPropertyValue from a JSON string
get_pet_types_success_response_result_pet_types_property_value_instance = GetPetTypesSuccessResponseResultPetTypesPropertyValue.from_json(json)
# print the JSON string representation of the object
print(GetPetTypesSuccessResponseResultPetTypesPropertyValue.to_json())

# convert the object into a dict
get_pet_types_success_response_result_pet_types_property_value_dict = get_pet_types_success_response_result_pet_types_property_value_instance.to_dict()
# create an instance of GetPetTypesSuccessResponseResultPetTypesPropertyValue from a dict
get_pet_types_success_response_result_pet_types_property_value_from_dict = GetPetTypesSuccessResponseResultPetTypesPropertyValue.from_dict(get_pet_types_success_response_result_pet_types_property_value_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



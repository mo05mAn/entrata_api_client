# GetPetTypesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **str** | Success response code | 
**result** | [**GetPetTypesSuccessResponseResult**](GetPetTypesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_pet_types_success_response import GetPetTypesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPetTypesSuccessResponse from a JSON string
get_pet_types_success_response_instance = GetPetTypesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetPetTypesSuccessResponse.to_json())

# convert the object into a dict
get_pet_types_success_response_dict = get_pet_types_success_response_instance.to_dict()
# create an instance of GetPetTypesSuccessResponse from a dict
get_pet_types_success_response_from_dict = GetPetTypesSuccessResponse.from_dict(get_pet_types_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



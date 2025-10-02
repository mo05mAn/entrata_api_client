# GetUnitTypesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **int** | Unique identifier for the request | 
**result** | [**GetUnitTypesSuccessResponseResponseResult**](GetUnitTypesSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_unit_types_success_response_response import GetUnitTypesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitTypesSuccessResponseResponse from a JSON string
get_unit_types_success_response_response_instance = GetUnitTypesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetUnitTypesSuccessResponseResponse.to_json())

# convert the object into a dict
get_unit_types_success_response_response_dict = get_unit_types_success_response_response_instance.to_dict()
# create an instance of GetUnitTypesSuccessResponseResponse from a dict
get_unit_types_success_response_response_from_dict = GetUnitTypesSuccessResponseResponse.from_dict(get_unit_types_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetPropertyUnitsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **int** | Request ID - The ID for the request | 
**result** | [**GetPropertyUnitsSuccessResponseResponseResult**](GetPropertyUnitsSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_property_units_success_response_response import GetPropertyUnitsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyUnitsSuccessResponseResponse from a JSON string
get_property_units_success_response_response_instance = GetPropertyUnitsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetPropertyUnitsSuccessResponseResponse.to_json())

# convert the object into a dict
get_property_units_success_response_response_dict = get_property_units_success_response_response_instance.to_dict()
# create an instance of GetPropertyUnitsSuccessResponseResponse from a dict
get_property_units_success_response_response_from_dict = GetPropertyUnitsSuccessResponseResponse.from_dict(get_property_units_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



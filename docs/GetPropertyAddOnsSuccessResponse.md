# GetPropertyAddOnsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **str** | Success response code | 
**result** | [**GetPropertyAddOnsSuccessResponseResult**](GetPropertyAddOnsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_property_add_ons_success_response import GetPropertyAddOnsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAddOnsSuccessResponse from a JSON string
get_property_add_ons_success_response_instance = GetPropertyAddOnsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAddOnsSuccessResponse.to_json())

# convert the object into a dict
get_property_add_ons_success_response_dict = get_property_add_ons_success_response_instance.to_dict()
# create an instance of GetPropertyAddOnsSuccessResponse from a dict
get_property_add_ons_success_response_from_dict = GetPropertyAddOnsSuccessResponse.from_dict(get_property_add_ons_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



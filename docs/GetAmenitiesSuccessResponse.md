# GetAmenitiesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**GetAmenitiesSuccessResponseResult**](GetAmenitiesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_amenities_success_response import GetAmenitiesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesSuccessResponse from a JSON string
get_amenities_success_response_instance = GetAmenitiesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesSuccessResponse.to_json())

# convert the object into a dict
get_amenities_success_response_dict = get_amenities_success_response_instance.to_dict()
# create an instance of GetAmenitiesSuccessResponse from a dict
get_amenities_success_response_from_dict = GetAmenitiesSuccessResponse.from_dict(get_amenities_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



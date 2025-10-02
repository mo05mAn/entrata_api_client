# GetLeasesR1SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **str** | Status code of the response | 
**result** | [**GetLeasesR1SuccessResponseResult**](GetLeasesR1SuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_leases_r1_success_response import GetLeasesR1SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR1SuccessResponse from a JSON string
get_leases_r1_success_response_instance = GetLeasesR1SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR1SuccessResponse.to_json())

# convert the object into a dict
get_leases_r1_success_response_dict = get_leases_r1_success_response_instance.to_dict()
# create an instance of GetLeasesR1SuccessResponse from a dict
get_leases_r1_success_response_from_dict = GetLeasesR1SuccessResponse.from_dict(get_leases_r1_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



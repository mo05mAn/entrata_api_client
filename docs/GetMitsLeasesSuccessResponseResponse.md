# GetMitsLeasesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**GetMitsLeasesSuccessResponseResponseResult**](GetMitsLeasesSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_mits_leases_success_response_response import GetMitsLeasesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeasesSuccessResponseResponse from a JSON string
get_mits_leases_success_response_response_instance = GetMitsLeasesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeasesSuccessResponseResponse.to_json())

# convert the object into a dict
get_mits_leases_success_response_response_dict = get_mits_leases_success_response_response_instance.to_dict()
# create an instance of GetMitsLeasesSuccessResponseResponse from a dict
get_mits_leases_success_response_response_from_dict = GetMitsLeasesSuccessResponseResponse.from_dict(get_mits_leases_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



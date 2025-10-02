# GetLeasesR2SuccessResponseResponse

The main response object

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Successful response code. | 
**result** | [**GetLeasesR2SuccessResponseResponseResult**](GetLeasesR2SuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_leases_r2_success_response_response import GetLeasesR2SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR2SuccessResponseResponse from a JSON string
get_leases_r2_success_response_response_instance = GetLeasesR2SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR2SuccessResponseResponse.to_json())

# convert the object into a dict
get_leases_r2_success_response_response_dict = get_leases_r2_success_response_response_instance.to_dict()
# create an instance of GetLeasesR2SuccessResponseResponse from a dict
get_leases_r2_success_response_response_from_dict = GetLeasesR2SuccessResponseResponse.from_dict(get_leases_r2_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



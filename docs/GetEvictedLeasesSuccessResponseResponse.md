# GetEvictedLeasesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **int** | Successful response code | 
**result** | [**GetEvictedLeasesSuccessResponseResponseResult**](GetEvictedLeasesSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_evicted_leases_success_response_response import GetEvictedLeasesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeasesSuccessResponseResponse from a JSON string
get_evicted_leases_success_response_response_instance = GetEvictedLeasesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeasesSuccessResponseResponse.to_json())

# convert the object into a dict
get_evicted_leases_success_response_response_dict = get_evicted_leases_success_response_response_instance.to_dict()
# create an instance of GetEvictedLeasesSuccessResponseResponse from a dict
get_evicted_leases_success_response_response_from_dict = GetEvictedLeasesSuccessResponseResponse.from_dict(get_evicted_leases_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



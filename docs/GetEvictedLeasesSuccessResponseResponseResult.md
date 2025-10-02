# GetEvictedLeasesSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**evicted_leases** | [**GetEvictedLeasesSuccessResponseResponseResultEvictedLeases**](GetEvictedLeasesSuccessResponseResponseResultEvictedLeases.md) |  | 

## Example

```python
from entrata_api_client.models.get_evicted_leases_success_response_response_result import GetEvictedLeasesSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeasesSuccessResponseResponseResult from a JSON string
get_evicted_leases_success_response_response_result_instance = GetEvictedLeasesSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeasesSuccessResponseResponseResult.to_json())

# convert the object into a dict
get_evicted_leases_success_response_response_result_dict = get_evicted_leases_success_response_response_result_instance.to_dict()
# create an instance of GetEvictedLeasesSuccessResponseResponseResult from a dict
get_evicted_leases_success_response_response_result_from_dict = GetEvictedLeasesSuccessResponseResponseResult.from_dict(get_evicted_leases_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



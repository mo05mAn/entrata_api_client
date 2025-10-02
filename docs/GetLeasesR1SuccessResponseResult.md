# GetLeasesR1SuccessResponseResult

The result object containing lease information

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**leases** | [**GetLeasesR1SuccessResponseResultLeases**](GetLeasesR1SuccessResponseResultLeases.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_leases_r1_success_response_result import GetLeasesR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR1SuccessResponseResult from a JSON string
get_leases_r1_success_response_result_instance = GetLeasesR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR1SuccessResponseResult.to_json())

# convert the object into a dict
get_leases_r1_success_response_result_dict = get_leases_r1_success_response_result_instance.to_dict()
# create an instance of GetLeasesR1SuccessResponseResult from a dict
get_leases_r1_success_response_result_from_dict = GetLeasesR1SuccessResponseResult.from_dict(get_leases_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



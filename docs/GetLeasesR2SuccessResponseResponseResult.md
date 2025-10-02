# GetLeasesR2SuccessResponseResponseResult

The result containing lease information

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency_code** | **str** | The currency code used in the lease | 
**leases** | [**GetLeasesR2SuccessResponseResponseResultLeases**](GetLeasesR2SuccessResponseResponseResultLeases.md) |  | 

## Example

```python
from entrata_api_client.models.get_leases_r2_success_response_response_result import GetLeasesR2SuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR2SuccessResponseResponseResult from a JSON string
get_leases_r2_success_response_response_result_instance = GetLeasesR2SuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR2SuccessResponseResponseResult.to_json())

# convert the object into a dict
get_leases_r2_success_response_response_result_dict = get_leases_r2_success_response_response_result_instance.to_dict()
# create an instance of GetLeasesR2SuccessResponseResponseResult from a dict
get_leases_r2_success_response_response_result_from_dict = GetLeasesR2SuccessResponseResponseResult.from_dict(get_leases_r2_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



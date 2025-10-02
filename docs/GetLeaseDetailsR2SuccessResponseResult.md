# GetLeaseDetailsR2SuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**leases** | [**GetLeaseDetailsR2SuccessResponseResultLeases**](GetLeaseDetailsR2SuccessResponseResultLeases.md) |  | 

## Example

```python
from openapi_client.models.get_lease_details_r2_success_response_result import GetLeaseDetailsR2SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR2SuccessResponseResult from a JSON string
get_lease_details_r2_success_response_result_instance = GetLeaseDetailsR2SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR2SuccessResponseResult.to_json())

# convert the object into a dict
get_lease_details_r2_success_response_result_dict = get_lease_details_r2_success_response_result_instance.to_dict()
# create an instance of GetLeaseDetailsR2SuccessResponseResult from a dict
get_lease_details_r2_success_response_result_from_dict = GetLeaseDetailsR2SuccessResponseResult.from_dict(get_lease_details_r2_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



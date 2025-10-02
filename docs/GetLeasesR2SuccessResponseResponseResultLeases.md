# GetLeasesR2SuccessResponseResponseResultLeases

Information about leases

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease** | [**List[GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner]**](GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner.md) | List of leases | 

## Example

```python
from openapi_client.models.get_leases_r2_success_response_response_result_leases import GetLeasesR2SuccessResponseResponseResultLeases

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR2SuccessResponseResponseResultLeases from a JSON string
get_leases_r2_success_response_response_result_leases_instance = GetLeasesR2SuccessResponseResponseResultLeases.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR2SuccessResponseResponseResultLeases.to_json())

# convert the object into a dict
get_leases_r2_success_response_response_result_leases_dict = get_leases_r2_success_response_response_result_leases_instance.to_dict()
# create an instance of GetLeasesR2SuccessResponseResponseResultLeases from a dict
get_leases_r2_success_response_response_result_leases_from_dict = GetLeasesR2SuccessResponseResponseResultLeases.from_dict(get_leases_r2_success_response_response_result_leases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



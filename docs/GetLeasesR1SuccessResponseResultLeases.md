# GetLeasesR1SuccessResponseResultLeases

The list of leases

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease** | [**List[GetLeasesR1SuccessResponseResultLeasesLeaseInner]**](GetLeasesR1SuccessResponseResultLeasesLeaseInner.md) | List of lease details | 

## Example

```python
from openapi_client.models.get_leases_r1_success_response_result_leases import GetLeasesR1SuccessResponseResultLeases

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR1SuccessResponseResultLeases from a JSON string
get_leases_r1_success_response_result_leases_instance = GetLeasesR1SuccessResponseResultLeases.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR1SuccessResponseResultLeases.to_json())

# convert the object into a dict
get_leases_r1_success_response_result_leases_dict = get_leases_r1_success_response_result_leases_instance.to_dict()
# create an instance of GetLeasesR1SuccessResponseResultLeases from a dict
get_leases_r1_success_response_result_leases_from_dict = GetLeasesR1SuccessResponseResultLeases.from_dict(get_leases_r1_success_response_result_leases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



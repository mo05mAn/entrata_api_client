# SendLeasesSuccessResponseResultLeasesLeaseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | Node identifier for the lease | 
**lease_id** | **str** | Unique identifier for the lease | 
**status** | **str** | Status of the lease insertion | 
**message** | **str** | Message detailing the result of the insertion | 

## Example

```python
from openapi_client.models.send_leases_success_response_result_leases_lease_inner import SendLeasesSuccessResponseResultLeasesLeaseInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeasesSuccessResponseResultLeasesLeaseInner from a JSON string
send_leases_success_response_result_leases_lease_inner_instance = SendLeasesSuccessResponseResultLeasesLeaseInner.from_json(json)
# print the JSON string representation of the object
print(SendLeasesSuccessResponseResultLeasesLeaseInner.to_json())

# convert the object into a dict
send_leases_success_response_result_leases_lease_inner_dict = send_leases_success_response_result_leases_lease_inner_instance.to_dict()
# create an instance of SendLeasesSuccessResponseResultLeasesLeaseInner from a dict
send_leases_success_response_result_leases_lease_inner_from_dict = SendLeasesSuccessResponseResultLeasesLeaseInner.from_dict(send_leases_success_response_result_leases_lease_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



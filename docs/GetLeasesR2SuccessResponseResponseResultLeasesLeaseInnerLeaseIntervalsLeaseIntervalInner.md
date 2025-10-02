# GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the lease interval | 
**start_date** | **str** | Start date of the lease interval | 
**end_date** | **str** | End date of the lease interval | 
**lease_interval_type_id** | **int** | ID of the lease interval type | 
**lease_interval_type_name** | **str** | Name of the lease interval type | 
**lease_interval_status_type_id** | **int** | ID of the lease interval status | 
**interval_date_time** | **str** | Date and time of the lease interval | 
**applications** | [**GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInnerApplications**](GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInnerApplications.md) |  | 

## Example

```python
from openapi_client.models.get_leases_r2_success_response_response_result_leases_lease_inner_lease_intervals_lease_interval_inner import GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner from a JSON string
get_leases_r2_success_response_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_instance = GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner.to_json())

# convert the object into a dict
get_leases_r2_success_response_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_dict = get_leases_r2_success_response_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_instance.to_dict()
# create an instance of GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner from a dict
get_leases_r2_success_response_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_from_dict = GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner.from_dict(get_leases_r2_success_response_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



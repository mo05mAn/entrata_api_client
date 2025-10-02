# GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the lease interval | 
**start_date** | **str** | Start date of the lease interval | 
**end_date** | **str** | End date of the lease interval | 
**lease_interval_type_id** | **str** | ID for the type of lease interval | 
**lease_interval_type_name** | **str** | Name of the lease interval type | 
**lease_interval_status_type_id** | **str** | ID for the lease interval status | 
**lease_interval_status_type_name** | **str** | Name of the lease interval status | 
**lease_approved_on** | **str** | Date when the lease was approved | 
**application_completed_on** | **str** | Date when the application was completed | 
**application_id** | **str** | ID for the application | 

## Example

```python
from entrata_api_client.models.get_leases_r1_success_response_result_leases_lease_inner_lease_intervals_lease_interval_inner import GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner from a JSON string
get_leases_r1_success_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_instance = GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner.to_json())

# convert the object into a dict
get_leases_r1_success_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_dict = get_leases_r1_success_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_instance.to_dict()
# create an instance of GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner from a dict
get_leases_r1_success_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_from_dict = GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervalsLeaseIntervalInner.from_dict(get_leases_r1_success_response_result_leases_lease_inner_lease_intervals_lease_interval_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



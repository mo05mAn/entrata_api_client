# GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**generation_time_stamp** | **str** | Timestamp when the report was generated. | 
**source_organization** | **str** | The source organization providing the report. | 
**total_properties** | **str** | Total number of properties. | 
**total_lease_files** | **str** | Total number of lease files. | 
**total_tenants** | **str** | Total number of tenants. | 
**total_open_amount** | **str** | Total open amount in dollars. | 

## Example

```python
from entrata_api_client.models.get_evicted_leases_success_response_response_result_evicted_leases_summary import GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesSummary

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesSummary from a JSON string
get_evicted_leases_success_response_response_result_evicted_leases_summary_instance = GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesSummary.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesSummary.to_json())

# convert the object into a dict
get_evicted_leases_success_response_response_result_evicted_leases_summary_dict = get_evicted_leases_success_response_response_result_evicted_leases_summary_instance.to_dict()
# create an instance of GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesSummary from a dict
get_evicted_leases_success_response_response_result_evicted_leases_summary_from_dict = GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesSummary.from_dict(get_evicted_leases_success_response_response_result_evicted_leases_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



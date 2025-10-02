# GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_id** | **str** | Unique identifier for the lease. | 
**eviction_status** | **str** | Status of the eviction (e.g., Evicted). | 
**move_in_date** | **str** | Move-in date. | 
**eviction_start_date** | **str** | Start date of eviction. | 
**eviction_date** | **str** | Date of eviction. | 
**lease_begin** | **str** | Lease start date. | 
**lease_end** | **str** | Lease end date. | 
**monthly_rent_amount** | **str** | Amount of monthly rent. | 
**rent_due_from_date** | **str** | Start date for rent due period. | 
**rent_due_to_date** | **str** | End date for rent due period. | 
**building_name** | **str** | Name of the building. | 
**unit** | [**GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerUnit**](GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerUnit.md) |  | 
**tenants** | [**GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenants**](GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenants.md) |  | 
**transactions** | [**GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTransactions**](GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTransactions.md) |  | 

## Example

```python
from entrata_api_client.models.get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner import GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInner from a JSON string
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_instance = GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInner.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInner.to_json())

# convert the object into a dict
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_dict = get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_instance.to_dict()
# create an instance of GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInner from a dict
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_from_dict = GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInner.from_dict(get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



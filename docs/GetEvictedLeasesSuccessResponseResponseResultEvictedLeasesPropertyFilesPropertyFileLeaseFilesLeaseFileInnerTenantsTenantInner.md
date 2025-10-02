# GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **str** | Unique identifier for the tenant. | 
**first_name** | **str** | First name of the tenant. | 
**last_name** | **str** | Last name of the tenant. | 
**customer_type** | **str** | Type of customer (e.g., Primary). | 
**phone** | [**List[GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInnerPhoneInner]**](GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInnerPhoneInner.md) |  | 
**date_of_birth** | **str** | Date of birth of the tenant. | 
**ssn** | **str** | Social Security Number. | 

## Example

```python
from openapi_client.models.get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_tenants_tenant_inner import GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInner from a JSON string
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_tenants_tenant_inner_instance = GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInner.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInner.to_json())

# convert the object into a dict
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_tenants_tenant_inner_dict = get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_tenants_tenant_inner_instance.to_dict()
# create an instance of GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInner from a dict
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_tenants_tenant_inner_from_dict = GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsTenantInner.from_dict(get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_lease_files_lease_file_inner_tenants_tenant_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



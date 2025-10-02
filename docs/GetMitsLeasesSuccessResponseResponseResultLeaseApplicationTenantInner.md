# GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**resident_type** | **str** | Type of the resident | 
**identification** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerIdentification**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerIdentification.md) |  | 
**lease_id** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerLeaseID**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerLeaseID.md) |  | 
**name** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerName**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerName.md) |  | 
**residence** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidence**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidence.md) |  | 
**phone** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerPhone**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerPhone.md) |  | 

## Example

```python
from openapi_client.models.get_mits_leases_success_response_response_result_lease_application_tenant_inner import GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner from a JSON string
get_mits_leases_success_response_response_result_lease_application_tenant_inner_instance = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner.to_json())

# convert the object into a dict
get_mits_leases_success_response_response_result_lease_application_tenant_inner_dict = get_mits_leases_success_response_response_result_lease_application_tenant_inner_instance.to_dict()
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner from a dict
get_mits_leases_success_response_response_result_lease_application_tenant_inner_from_dict = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner.from_dict(get_mits_leases_success_response_response_result_lease_application_tenant_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



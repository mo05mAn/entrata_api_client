# GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidenceAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_type** | **str** | Type of the address | 
**address** | **str** | Address of the tenant | 
**city** | **str** | City of the residence | 
**state** | **str** | State of the residence | 
**postal_code** | **str** | Postal code of the residence | 
**email** | **str** | Email address of the tenant | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_leases_success_response_response_result_lease_application_tenant_inner_residence_address import GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidenceAddress

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidenceAddress from a JSON string
get_mits_leases_success_response_response_result_lease_application_tenant_inner_residence_address_instance = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidenceAddress.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidenceAddress.to_json())

# convert the object into a dict
get_mits_leases_success_response_response_result_lease_application_tenant_inner_residence_address_dict = get_mits_leases_success_response_response_result_lease_application_tenant_inner_residence_address_instance.to_dict()
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidenceAddress from a dict
get_mits_leases_success_response_response_result_lease_application_tenant_inner_residence_address_from_dict = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInnerResidenceAddress.from_dict(get_mits_leases_success_response_response_result_lease_application_tenant_inner_residence_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



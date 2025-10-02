# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerIdentification**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerIdentification.md) |  | 
**lease_id** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerLeaseID**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerLeaseID.md) |  | 
**name** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerName**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerName.md) |  | 
**residence** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidence**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidence.md) |  | 
**phone** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerPhone**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerPhone.md) |  | [optional] 
**attributes** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerAttributes**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerAttributes.md) |  | 

## Example

```python
from openapi_client.models.get_renters_insurance_policies_success_response_result_lease_application_tenant_inner import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_dict = get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner from a dict
get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner.from_dict(get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



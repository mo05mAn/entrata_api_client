# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | Street address of the tenant | 
**city** | **str** | City of the tenant&#39;s residence | 
**state** | **str** | State of the tenant&#39;s residence | 
**postal_code** | **str** | Postal code of the tenant&#39;s residence | 
**country_name** | **str** | Country of the tenant&#39;s residence | 
**email** | **str** | Email address of the tenant | [optional] 
**attributes** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddressAttributes**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddressAttributes.md) |  | 

## Example

```python
from openapi_client.models.get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_residence_address import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddress

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddress from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_residence_address_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddress.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddress.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_residence_address_dict = get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_residence_address_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddress from a dict
get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_residence_address_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInnerResidenceAddress.from_dict(get_renters_insurance_policies_success_response_result_lease_application_tenant_inner_residence_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



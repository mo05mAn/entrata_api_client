# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_property** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty.md) |  | 
**tenant** | [**List[GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner]**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationTenantInner.md) |  | 
**la_lease** | [**List[GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner]**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner.md) |  | 

## Example

```python
from entrata_api_client.models.get_renters_insurance_policies_success_response_result_lease_application import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplication

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplication from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplication.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplication.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_dict = get_renters_insurance_policies_success_response_result_lease_application_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplication from a dict
get_renters_insurance_policies_success_response_result_lease_application_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplication.from_dict(get_renters_insurance_policies_success_response_result_lease_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



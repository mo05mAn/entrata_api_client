# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerIdentification**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerIdentification.md) |  | 
**status** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerStatus**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerStatus.md) |  | 
**unit** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit.md) |  | 
**insurance_policies** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePolicies**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePolicies.md) |  | 

## Example

```python
from openapi_client.models.get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_dict = get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner from a dict
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInner.from_dict(get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



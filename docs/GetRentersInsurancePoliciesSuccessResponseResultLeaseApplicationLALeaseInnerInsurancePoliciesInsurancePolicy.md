# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePoliciesInsurancePolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Insurance policy ID | 
**name** | **str** | Insurance policy name | 
**unit_number** | **str** | Unit number | 
**lease_id** | **str** | Lease ID associated with the insurance policy | 
**customer_id** | **str** | Customer ID associated with the insurance policy | 
**policy_number** | **str** | Insurance policy number | 
**start_date** | **str** | Start date of the insurance policy | 
**liability** | **str** | Liability coverage amount | 
**deductible** | **str** | Insurance policy deductible | 
**personal_contents** | **str** | Personal contents coverage | 
**policy_type_id** | **int** | ID for the type of insurance policy | 
**policy_type_name** | **str** | Name of the insurance policy type | 

## Example

```python
from entrata_api_client.models.get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_insurance_policies_insurance_policy import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePoliciesInsurancePolicy

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePoliciesInsurancePolicy from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_insurance_policies_insurance_policy_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePoliciesInsurancePolicy.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePoliciesInsurancePolicy.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_insurance_policies_insurance_policy_dict = get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_insurance_policies_insurance_policy_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePoliciesInsurancePolicy from a dict
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_insurance_policies_insurance_policy_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerInsurancePoliciesInsurancePolicy.from_dict(get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_insurance_policies_insurance_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



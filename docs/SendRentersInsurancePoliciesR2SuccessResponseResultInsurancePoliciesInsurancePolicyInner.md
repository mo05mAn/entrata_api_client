# SendRentersInsurancePoliciesR2SuccessResponseResultInsurancePoliciesInsurancePolicyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | Node identifier for the insurance policy | 
**reference_id** | **str** | Unique reference ID for the insurance policy | 
**lease_id** | **str** | Unique identifier for the lease associated with the policy | 
**customer_id** | **str** | Comma-separated list of customer IDs associated with the insurance policy | 
**status** | **str** | Status of the insurance policy update or insertion | 
**message** | **str** | Message detailing the result of the policy update or insertion | 

## Example

```python
from entrata_api_client.models.send_renters_insurance_policies_r2_success_response_result_insurance_policies_insurance_policy_inner import SendRentersInsurancePoliciesR2SuccessResponseResultInsurancePoliciesInsurancePolicyInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR2SuccessResponseResultInsurancePoliciesInsurancePolicyInner from a JSON string
send_renters_insurance_policies_r2_success_response_result_insurance_policies_insurance_policy_inner_instance = SendRentersInsurancePoliciesR2SuccessResponseResultInsurancePoliciesInsurancePolicyInner.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR2SuccessResponseResultInsurancePoliciesInsurancePolicyInner.to_json())

# convert the object into a dict
send_renters_insurance_policies_r2_success_response_result_insurance_policies_insurance_policy_inner_dict = send_renters_insurance_policies_r2_success_response_result_insurance_policies_insurance_policy_inner_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR2SuccessResponseResultInsurancePoliciesInsurancePolicyInner from a dict
send_renters_insurance_policies_r2_success_response_result_insurance_policies_insurance_policy_inner_from_dict = SendRentersInsurancePoliciesR2SuccessResponseResultInsurancePoliciesInsurancePolicyInner.from_dict(send_renters_insurance_policies_r2_success_response_result_insurance_policies_insurance_policy_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



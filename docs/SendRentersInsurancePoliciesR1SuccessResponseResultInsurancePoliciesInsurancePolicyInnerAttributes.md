# SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePoliciesInsurancePolicyInnerAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | Node identifier for the insurance policy | 
**reference_id** | **str** | Unique reference ID for the insurance policy | 
**lease_id** | **str** | Unique identifier for the lease associated with the policy | 
**customer_id** | **str** | Unique identifier for the customer associated with the policy | 
**status** | **str** | Status of the insurance policy update or insertion | 
**message** | **str** | Message detailing the result of the policy update or insertion | 

## Example

```python
from entrata_api_client.models.send_renters_insurance_policies_r1_success_response_result_insurance_policies_insurance_policy_inner_attributes import SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePoliciesInsurancePolicyInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePoliciesInsurancePolicyInnerAttributes from a JSON string
send_renters_insurance_policies_r1_success_response_result_insurance_policies_insurance_policy_inner_attributes_instance = SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePoliciesInsurancePolicyInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePoliciesInsurancePolicyInnerAttributes.to_json())

# convert the object into a dict
send_renters_insurance_policies_r1_success_response_result_insurance_policies_insurance_policy_inner_attributes_dict = send_renters_insurance_policies_r1_success_response_result_insurance_policies_insurance_policy_inner_attributes_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePoliciesInsurancePolicyInnerAttributes from a dict
send_renters_insurance_policies_r1_success_response_result_insurance_policies_insurance_policy_inner_attributes_from_dict = SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePoliciesInsurancePolicyInnerAttributes.from_dict(send_renters_insurance_policies_r1_success_response_result_insurance_policies_insurance_policy_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# SendRentersInsurancePoliciesR1SuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**insurance_policies** | [**SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePolicies**](SendRentersInsurancePoliciesR1SuccessResponseResultInsurancePolicies.md) |  | 

## Example

```python
from entrata_api_client.models.send_renters_insurance_policies_r1_success_response_result import SendRentersInsurancePoliciesR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR1SuccessResponseResult from a JSON string
send_renters_insurance_policies_r1_success_response_result_instance = SendRentersInsurancePoliciesR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR1SuccessResponseResult.to_json())

# convert the object into a dict
send_renters_insurance_policies_r1_success_response_result_dict = send_renters_insurance_policies_r1_success_response_result_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR1SuccessResponseResult from a dict
send_renters_insurance_policies_r1_success_response_result_from_dict = SendRentersInsurancePoliciesR1SuccessResponseResult.from_dict(send_renters_insurance_policies_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



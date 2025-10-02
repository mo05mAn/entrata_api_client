# SendRentersInsurancePoliciesR2SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response status code | 
**result** | [**SendRentersInsurancePoliciesR2SuccessResponseResult**](SendRentersInsurancePoliciesR2SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_renters_insurance_policies_r2_success_response import SendRentersInsurancePoliciesR2SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR2SuccessResponse from a JSON string
send_renters_insurance_policies_r2_success_response_instance = SendRentersInsurancePoliciesR2SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR2SuccessResponse.to_json())

# convert the object into a dict
send_renters_insurance_policies_r2_success_response_dict = send_renters_insurance_policies_r2_success_response_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR2SuccessResponse from a dict
send_renters_insurance_policies_r2_success_response_from_dict = SendRentersInsurancePoliciesR2SuccessResponse.from_dict(send_renters_insurance_policies_r2_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



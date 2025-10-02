# SendRentersInsurancePoliciesR1SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response status code | 
**result** | [**SendRentersInsurancePoliciesR1SuccessResponseResult**](SendRentersInsurancePoliciesR1SuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_renters_insurance_policies_r1_success_response import SendRentersInsurancePoliciesR1SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR1SuccessResponse from a JSON string
send_renters_insurance_policies_r1_success_response_instance = SendRentersInsurancePoliciesR1SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR1SuccessResponse.to_json())

# convert the object into a dict
send_renters_insurance_policies_r1_success_response_dict = send_renters_insurance_policies_r1_success_response_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR1SuccessResponse from a dict
send_renters_insurance_policies_r1_success_response_from_dict = SendRentersInsurancePoliciesR1SuccessResponse.from_dict(send_renters_insurance_policies_r1_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



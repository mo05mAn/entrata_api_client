# GetRentersInsurancePoliciesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | [optional] 
**code** | **str** | Response status code | [optional] 
**result** | [**GetRentersInsurancePoliciesSuccessResponseResult**](GetRentersInsurancePoliciesSuccessResponseResult.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_renters_insurance_policies_success_response import GetRentersInsurancePoliciesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponse from a JSON string
get_renters_insurance_policies_success_response_instance = GetRentersInsurancePoliciesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponse.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_dict = get_renters_insurance_policies_success_response_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponse from a dict
get_renters_insurance_policies_success_response_from_dict = GetRentersInsurancePoliciesSuccessResponse.from_dict(get_renters_insurance_policies_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



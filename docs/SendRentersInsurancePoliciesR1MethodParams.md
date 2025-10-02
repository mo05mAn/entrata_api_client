# SendRentersInsurancePoliciesR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**id** | **int** | This is an optional field. This field accepts single value. Insurance policy id | [optional] 
**lease_id** | **int** | This is a required field. This field accepts single value. leaseId | 
**customer_id** | **int** | This is a required field. This field accepts single value. customerId | 
**provider** | **str** | This is a required field. This field accepts single value. provider | 
**policy_number** | **str** | This is a required field. This field accepts single value. policyNumber | 
**start_date** | **date** | This is a required field. This field accepts single value. startDate | 
**end_date** | **date** | This is a required field. This field accepts single value. endDate | 
**liability** | **int** | This is a required field. This field accepts single value. liability | 

## Example

```python
from entrata_api_client.models.send_renters_insurance_policies_r1_method_params import SendRentersInsurancePoliciesR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR1MethodParams from a JSON string
send_renters_insurance_policies_r1_method_params_instance = SendRentersInsurancePoliciesR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR1MethodParams.to_json())

# convert the object into a dict
send_renters_insurance_policies_r1_method_params_dict = send_renters_insurance_policies_r1_method_params_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR1MethodParams from a dict
send_renters_insurance_policies_r1_method_params_from_dict = SendRentersInsurancePoliciesR1MethodParams.from_dict(send_renters_insurance_policies_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



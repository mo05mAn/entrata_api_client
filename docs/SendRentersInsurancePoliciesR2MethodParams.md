# SendRentersInsurancePoliciesR2MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**id** | **int** | This is an optional field. This field accepts single value. Insurance policy id | [optional] 
**lease_id** | **int** | This is a required field. This field accepts single value. leaseId | 
**customer_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. customerIds | [optional] 
**provider** | **str** | This is a required field. This field accepts single value. provider | 
**policy_number** | **str** | This is a required field. This field accepts single value. policyNumber | 
**start_date** | **date** | This is a required field. This field accepts single value. startDate | 
**end_date** | **date** | This is a required field. This field accepts single value. endDate | 
**liability** | **int** | This is a required field. This field accepts single value. liability | 
**personal_contents** | **int** | This is an optional field. This field accepts single value. personalContents | [optional] 
**deductible** | **int** | This is an optional field. This field accepts single value. deductible | [optional] 
**is_cancelled** | **int** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.send_renters_insurance_policies_r2_method_params import SendRentersInsurancePoliciesR2MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR2MethodParams from a JSON string
send_renters_insurance_policies_r2_method_params_instance = SendRentersInsurancePoliciesR2MethodParams.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR2MethodParams.to_json())

# convert the object into a dict
send_renters_insurance_policies_r2_method_params_dict = send_renters_insurance_policies_r2_method_params_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR2MethodParams from a dict
send_renters_insurance_policies_r2_method_params_from_dict = SendRentersInsurancePoliciesR2MethodParams.from_dict(send_renters_insurance_policies_r2_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



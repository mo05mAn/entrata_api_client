# GetRentersInsurancePoliciesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetRentersInsurancePoliciesMethodParams**](GetRentersInsurancePoliciesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_renters_insurance_policies_method import GetRentersInsurancePoliciesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesMethod from a JSON string
get_renters_insurance_policies_method_instance = GetRentersInsurancePoliciesMethod.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesMethod.to_json())

# convert the object into a dict
get_renters_insurance_policies_method_dict = get_renters_insurance_policies_method_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesMethod from a dict
get_renters_insurance_policies_method_from_dict = GetRentersInsurancePoliciesMethod.from_dict(get_renters_insurance_policies_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



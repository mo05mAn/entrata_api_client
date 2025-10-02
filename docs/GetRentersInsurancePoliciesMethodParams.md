# GetRentersInsurancePoliciesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property id | 
**lease_status_type_ids** | **int** | This is an optional field. This field accepts single value. leaseStatusTypeIds | [optional] 
**last_updated_on** | **date** | This is an optional field. This field accepts single value. lastUpdatedOn | [optional] 

## Example

```python
from entrata_api_client.models.get_renters_insurance_policies_method_params import GetRentersInsurancePoliciesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesMethodParams from a JSON string
get_renters_insurance_policies_method_params_instance = GetRentersInsurancePoliciesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesMethodParams.to_json())

# convert the object into a dict
get_renters_insurance_policies_method_params_dict = get_renters_insurance_policies_method_params_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesMethodParams from a dict
get_renters_insurance_policies_method_params_from_dict = GetRentersInsurancePoliciesMethodParams.from_dict(get_renters_insurance_policies_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



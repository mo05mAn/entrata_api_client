# GetRentersInsurancePolicies


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetRentersInsurancePoliciesMethod**](GetRentersInsurancePoliciesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_renters_insurance_policies import GetRentersInsurancePolicies

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePolicies from a JSON string
get_renters_insurance_policies_instance = GetRentersInsurancePolicies.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePolicies.to_json())

# convert the object into a dict
get_renters_insurance_policies_dict = get_renters_insurance_policies_instance.to_dict()
# create an instance of GetRentersInsurancePolicies from a dict
get_renters_insurance_policies_from_dict = GetRentersInsurancePolicies.from_dict(get_renters_insurance_policies_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



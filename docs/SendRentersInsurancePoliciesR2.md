# SendRentersInsurancePoliciesR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendRentersInsurancePoliciesR2Method**](SendRentersInsurancePoliciesR2Method.md) |  | 

## Example

```python
from entrata_api_client.models.send_renters_insurance_policies_r2 import SendRentersInsurancePoliciesR2

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR2 from a JSON string
send_renters_insurance_policies_r2_instance = SendRentersInsurancePoliciesR2.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR2.to_json())

# convert the object into a dict
send_renters_insurance_policies_r2_dict = send_renters_insurance_policies_r2_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR2 from a dict
send_renters_insurance_policies_r2_from_dict = SendRentersInsurancePoliciesR2.from_dict(send_renters_insurance_policies_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# SendRentersInsurancePoliciesR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendRentersInsurancePoliciesR1Method**](SendRentersInsurancePoliciesR1Method.md) |  | 

## Example

```python
from entrata_api_client.models.send_renters_insurance_policies_r1 import SendRentersInsurancePoliciesR1

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentersInsurancePoliciesR1 from a JSON string
send_renters_insurance_policies_r1_instance = SendRentersInsurancePoliciesR1.from_json(json)
# print the JSON string representation of the object
print(SendRentersInsurancePoliciesR1.to_json())

# convert the object into a dict
send_renters_insurance_policies_r1_dict = send_renters_insurance_policies_r1_instance.to_dict()
# create an instance of SendRentersInsurancePoliciesR1 from a dict
send_renters_insurance_policies_r1_from_dict = SendRentersInsurancePoliciesR1.from_dict(send_renters_insurance_policies_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



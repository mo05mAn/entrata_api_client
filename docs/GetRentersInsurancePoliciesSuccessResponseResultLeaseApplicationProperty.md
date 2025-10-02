# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyIdentification.md) |  | 
**marketing_name** | **str** | Marketing name for the property | 
**address** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress.md) |  | 

## Example

```python
from entrata_api_client.models.get_renters_insurance_policies_success_response_result_lease_application_property import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_property_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_property_dict = get_renters_insurance_policies_success_response_result_lease_application_property_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty from a dict
get_renters_insurance_policies_success_response_result_lease_application_property_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationProperty.from_dict(get_renters_insurance_policies_success_response_result_lease_application_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



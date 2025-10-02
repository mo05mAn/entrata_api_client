# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** | Description of the address | 
**address** | **str** | Street address | 
**city** | **str** | City of the property | 
**state** | **str** | State of the property | 
**postal_code** | **str** | Postal code of the property | 
**country** | **str** | Country of the property | 
**attributes** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddressAttributes**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddressAttributes.md) |  | 

## Example

```python
from openapi_client.models.get_renters_insurance_policies_success_response_result_lease_application_property_address import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_property_address_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_property_address_dict = get_renters_insurance_policies_success_response_result_lease_application_property_address_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress from a dict
get_renters_insurance_policies_success_response_result_lease_application_property_address_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationPropertyAddress.from_dict(get_renters_insurance_policies_success_response_result_lease_application_property_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



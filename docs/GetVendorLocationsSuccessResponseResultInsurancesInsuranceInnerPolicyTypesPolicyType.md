# GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Type of insurance policy. | 
**policy_number** | **str** | Policy number. | 
**expiration** | **str** | Expiration date of the policy. | 
**coverages** | [**GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyTypeCoverages**](GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyTypeCoverages.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendor_locations_success_response_result_insurances_insurance_inner_policy_types_policy_type import GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyType

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyType from a JSON string
get_vendor_locations_success_response_result_insurances_insurance_inner_policy_types_policy_type_instance = GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyType.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyType.to_json())

# convert the object into a dict
get_vendor_locations_success_response_result_insurances_insurance_inner_policy_types_policy_type_dict = get_vendor_locations_success_response_result_insurances_insurance_inner_policy_types_policy_type_instance.to_dict()
# create an instance of GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyType from a dict
get_vendor_locations_success_response_result_insurances_insurance_inner_policy_types_policy_type_from_dict = GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypesPolicyType.from_dict(get_vendor_locations_success_response_result_insurances_insurance_inner_policy_types_policy_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



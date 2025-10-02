# GetVendorLocationsSuccessResponseResultInsurancesInsuranceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_id** | **str** | Unique identifier for the vendor. | 
**policy_types** | [**GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypes**](GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerPolicyTypes.md) |  | 
**attributes** | [**GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerAttributes**](GetVendorLocationsSuccessResponseResultInsurancesInsuranceInnerAttributes.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendor_locations_success_response_result_insurances_insurance_inner import GetVendorLocationsSuccessResponseResultInsurancesInsuranceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsSuccessResponseResultInsurancesInsuranceInner from a JSON string
get_vendor_locations_success_response_result_insurances_insurance_inner_instance = GetVendorLocationsSuccessResponseResultInsurancesInsuranceInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsSuccessResponseResultInsurancesInsuranceInner.to_json())

# convert the object into a dict
get_vendor_locations_success_response_result_insurances_insurance_inner_dict = get_vendor_locations_success_response_result_insurances_insurance_inner_instance.to_dict()
# create an instance of GetVendorLocationsSuccessResponseResultInsurancesInsuranceInner from a dict
get_vendor_locations_success_response_result_insurances_insurance_inner_from_dict = GetVendorLocationsSuccessResponseResultInsurancesInsuranceInner.from_dict(get_vendor_locations_success_response_result_insurances_insurance_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



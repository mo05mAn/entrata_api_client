# GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnitIdentification**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnitIdentification.md) |  | 
**marketing_name** | **str** | Marketing name of the property unit | 
**unit_type** | **str** | Type of the unit | 
**unit_bedrooms** | **str** | Number of bedrooms in the unit | 
**unit_bathrooms** | **str** | Number of bathrooms in the unit | 
**square_foot_type** | **str** | Type of square footage measurement | 
**unit_economic_status** | **str** | Economic status of the unit | 
**unit_leased_status** | **str** | Leased status of the unit | 
**number_occupants** | [**GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnitNumberOccupants**](GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnitNumberOccupants.md) |  | 
**building_name** | **str** | Building name | 

## Example

```python
from openapi_client.models.get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_unit import GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit from a JSON string
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_unit_instance = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit.from_json(json)
# print the JSON string representation of the object
print(GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit.to_json())

# convert the object into a dict
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_unit_dict = get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_unit_instance.to_dict()
# create an instance of GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit from a dict
get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_unit_from_dict = GetRentersInsurancePoliciesSuccessResponseResultLeaseApplicationLALeaseInnerUnit.from_dict(get_renters_insurance_policies_success_response_result_lease_application_la_lease_inner_unit_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



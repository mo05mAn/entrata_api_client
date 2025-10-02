# GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInnerAttributes

Attributes of each charge code type

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier for the charge code type | [optional] 
**name** | **str** | Name of the charge code type | [optional] 
**allowed_charge_timing_ids** | **str** | Comma-separated list of allowed charge timing IDs for the charge code type | [optional] 

## Example

```python
from entrata_api_client.models.get_pricing_picklists_success_response_response_result_charge_code_types_charge_code_type_inner_attributes import GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInnerAttributes from a JSON string
get_pricing_picklists_success_response_response_result_charge_code_types_charge_code_type_inner_attributes_instance = GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInnerAttributes.to_json())

# convert the object into a dict
get_pricing_picklists_success_response_response_result_charge_code_types_charge_code_type_inner_attributes_dict = get_pricing_picklists_success_response_response_result_charge_code_types_charge_code_type_inner_attributes_instance.to_dict()
# create an instance of GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInnerAttributes from a dict
get_pricing_picklists_success_response_response_result_charge_code_types_charge_code_type_inner_attributes_from_dict = GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInnerAttributes.from_dict(get_pricing_picklists_success_response_response_result_charge_code_types_charge_code_type_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



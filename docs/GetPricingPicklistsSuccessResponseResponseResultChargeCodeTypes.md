# GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes

Charge code types details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**charge_code_type** | [**List[GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInner]**](GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypesChargeCodeTypeInner.md) | List of charge code types | [optional] 

## Example

```python
from entrata_api_client.models.get_pricing_picklists_success_response_response_result_charge_code_types import GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes

# TODO update the JSON string below
json = "{}"
# create an instance of GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes from a JSON string
get_pricing_picklists_success_response_response_result_charge_code_types_instance = GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes.from_json(json)
# print the JSON string representation of the object
print(GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes.to_json())

# convert the object into a dict
get_pricing_picklists_success_response_response_result_charge_code_types_dict = get_pricing_picklists_success_response_response_result_charge_code_types_instance.to_dict()
# create an instance of GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes from a dict
get_pricing_picklists_success_response_response_result_charge_code_types_from_dict = GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes.from_dict(get_pricing_picklists_success_response_response_result_charge_code_types_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



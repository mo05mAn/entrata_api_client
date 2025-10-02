# GetPricingPicklistsSuccessResponseResponseResult

The result containing pricing levels, charge usages, charge timings, and charge code types

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pricing_levels** | [**GetPricingPicklistsSuccessResponseResponseResultPricingLevels**](GetPricingPicklistsSuccessResponseResponseResultPricingLevels.md) |  | [optional] 
**charge_usages** | [**GetPricingPicklistsSuccessResponseResponseResultChargeUsages**](GetPricingPicklistsSuccessResponseResponseResultChargeUsages.md) |  | [optional] 
**charge_timings** | [**GetPricingPicklistsSuccessResponseResponseResultChargeTimings**](GetPricingPicklistsSuccessResponseResponseResultChargeTimings.md) |  | [optional] 
**charge_code_types** | [**GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes**](GetPricingPicklistsSuccessResponseResponseResultChargeCodeTypes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_pricing_picklists_success_response_response_result import GetPricingPicklistsSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPricingPicklistsSuccessResponseResponseResult from a JSON string
get_pricing_picklists_success_response_response_result_instance = GetPricingPicklistsSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPricingPicklistsSuccessResponseResponseResult.to_json())

# convert the object into a dict
get_pricing_picklists_success_response_response_result_dict = get_pricing_picklists_success_response_response_result_instance.to_dict()
# create an instance of GetPricingPicklistsSuccessResponseResponseResult from a dict
get_pricing_picklists_success_response_response_result_from_dict = GetPricingPicklistsSuccessResponseResponseResult.from_dict(get_pricing_picklists_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



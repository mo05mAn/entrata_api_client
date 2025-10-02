# GetPricingPicklistsSuccessResponseResponseResultChargeUsages

Charge usages details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**charge_usage** | [**List[GetPricingPicklistsSuccessResponseResponseResultChargeUsagesChargeUsageInner]**](GetPricingPicklistsSuccessResponseResponseResultChargeUsagesChargeUsageInner.md) | List of charge usages | [optional] 

## Example

```python
from openapi_client.models.get_pricing_picklists_success_response_response_result_charge_usages import GetPricingPicklistsSuccessResponseResponseResultChargeUsages

# TODO update the JSON string below
json = "{}"
# create an instance of GetPricingPicklistsSuccessResponseResponseResultChargeUsages from a JSON string
get_pricing_picklists_success_response_response_result_charge_usages_instance = GetPricingPicklistsSuccessResponseResponseResultChargeUsages.from_json(json)
# print the JSON string representation of the object
print(GetPricingPicklistsSuccessResponseResponseResultChargeUsages.to_json())

# convert the object into a dict
get_pricing_picklists_success_response_response_result_charge_usages_dict = get_pricing_picklists_success_response_response_result_charge_usages_instance.to_dict()
# create an instance of GetPricingPicklistsSuccessResponseResponseResultChargeUsages from a dict
get_pricing_picklists_success_response_response_result_charge_usages_from_dict = GetPricingPicklistsSuccessResponseResponseResultChargeUsages.from_dict(get_pricing_picklists_success_response_response_result_charge_usages_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



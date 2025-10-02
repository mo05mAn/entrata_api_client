# GetPricingPicklistsSuccessResponseResponseResultPricingLevels

Pricing levels details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pricing_level** | [**List[GetPricingPicklistsSuccessResponseResponseResultPricingLevelsPricingLevelInner]**](GetPricingPicklistsSuccessResponseResponseResultPricingLevelsPricingLevelInner.md) | List of pricing levels | [optional] 

## Example

```python
from openapi_client.models.get_pricing_picklists_success_response_response_result_pricing_levels import GetPricingPicklistsSuccessResponseResponseResultPricingLevels

# TODO update the JSON string below
json = "{}"
# create an instance of GetPricingPicklistsSuccessResponseResponseResultPricingLevels from a JSON string
get_pricing_picklists_success_response_response_result_pricing_levels_instance = GetPricingPicklistsSuccessResponseResponseResultPricingLevels.from_json(json)
# print the JSON string representation of the object
print(GetPricingPicklistsSuccessResponseResponseResultPricingLevels.to_json())

# convert the object into a dict
get_pricing_picklists_success_response_response_result_pricing_levels_dict = get_pricing_picklists_success_response_response_result_pricing_levels_instance.to_dict()
# create an instance of GetPricingPicklistsSuccessResponseResponseResultPricingLevels from a dict
get_pricing_picklists_success_response_response_result_pricing_levels_from_dict = GetPricingPicklistsSuccessResponseResponseResultPricingLevels.from_dict(get_pricing_picklists_success_response_response_result_pricing_levels_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



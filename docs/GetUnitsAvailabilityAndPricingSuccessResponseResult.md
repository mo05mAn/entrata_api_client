# GetUnitsAvailabilityAndPricingSuccessResponseResult

Result object containing properties and units

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**properties** | [**GetUnitsAvailabilityAndPricingSuccessResponseResultProperties**](GetUnitsAvailabilityAndPricingSuccessResponseResultProperties.md) |  | 
**property_units** | [**GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits.md) |  | 

## Example

```python
from openapi_client.models.get_units_availability_and_pricing_success_response_result import GetUnitsAvailabilityAndPricingSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResult from a JSON string
get_units_availability_and_pricing_success_response_result_instance = GetUnitsAvailabilityAndPricingSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetUnitsAvailabilityAndPricingSuccessResponseResult.to_json())

# convert the object into a dict
get_units_availability_and_pricing_success_response_result_dict = get_units_availability_and_pricing_success_response_result_instance.to_dict()
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResult from a dict
get_units_availability_and_pricing_success_response_result_from_dict = GetUnitsAvailabilityAndPricingSuccessResponseResult.from_dict(get_units_availability_and_pricing_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



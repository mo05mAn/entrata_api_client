# GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits

Details about available units in the property

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_unit** | [**List[GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInner]**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInner.md) | List of available units | 

## Example

```python
from openapi_client.models.get_units_availability_and_pricing_success_response_result_property_units import GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits from a JSON string
get_units_availability_and_pricing_success_response_result_property_units_instance = GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits.from_json(json)
# print the JSON string representation of the object
print(GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits.to_json())

# convert the object into a dict
get_units_availability_and_pricing_success_response_result_property_units_dict = get_units_availability_and_pricing_success_response_result_property_units_instance.to_dict()
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits from a dict
get_units_availability_and_pricing_success_response_result_property_units_from_dict = GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnits.from_dict(get_units_availability_and_pricing_success_response_result_property_units_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



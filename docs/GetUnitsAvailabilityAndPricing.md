# GetUnitsAvailabilityAndPricing


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetUnitsAvailabilityAndPricingMethod**](GetUnitsAvailabilityAndPricingMethod.md) |  | 

## Example

```python
from openapi_client.models.get_units_availability_and_pricing import GetUnitsAvailabilityAndPricing

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitsAvailabilityAndPricing from a JSON string
get_units_availability_and_pricing_instance = GetUnitsAvailabilityAndPricing.from_json(json)
# print the JSON string representation of the object
print(GetUnitsAvailabilityAndPricing.to_json())

# convert the object into a dict
get_units_availability_and_pricing_dict = get_units_availability_and_pricing_instance.to_dict()
# create an instance of GetUnitsAvailabilityAndPricing from a dict
get_units_availability_and_pricing_from_dict = GetUnitsAvailabilityAndPricing.from_dict(get_units_availability_and_pricing_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



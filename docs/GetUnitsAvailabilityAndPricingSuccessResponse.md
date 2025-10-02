# GetUnitsAvailabilityAndPricingSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique request identifier | [optional] 
**result** | [**GetUnitsAvailabilityAndPricingSuccessResponseResult**](GetUnitsAvailabilityAndPricingSuccessResponseResult.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_units_availability_and_pricing_success_response import GetUnitsAvailabilityAndPricingSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponse from a JSON string
get_units_availability_and_pricing_success_response_instance = GetUnitsAvailabilityAndPricingSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetUnitsAvailabilityAndPricingSuccessResponse.to_json())

# convert the object into a dict
get_units_availability_and_pricing_success_response_dict = get_units_availability_and_pricing_success_response_instance.to_dict()
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponse from a dict
get_units_availability_and_pricing_success_response_from_dict = GetUnitsAvailabilityAndPricingSuccessResponse.from_dict(get_units_availability_and_pricing_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



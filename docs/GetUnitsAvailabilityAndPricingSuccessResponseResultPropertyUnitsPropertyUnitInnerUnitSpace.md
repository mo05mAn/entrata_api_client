# GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpace

Information about each unit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rent** | [**GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpaceRent**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpaceRent.md) |  | 
**deposit** | [**GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpaceDeposit**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpaceDeposit.md) |  | 
**unit_number** | **str** | Unit number | 
**availability** | **str** | Availability status of the unit | [optional] 
**status** | **str** | Current status of the unit | [optional] 
**available_on** | **str** | Date when the unit becomes available | [optional] 
**occupancy_type** | **str** | Type of occupancy for the unit | [optional] 
**is_affordable** | **int** | Whether the unit is affordable | [optional] 
**has_pricing** | **int** | Whether pricing is available for the unit | [optional] 
**area** | **str** | Area of the unit in square meters | [optional] 

## Example

```python
from openapi_client.models.get_units_availability_and_pricing_success_response_result_property_units_property_unit_inner_unit_space import GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpace

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpace from a JSON string
get_units_availability_and_pricing_success_response_result_property_units_property_unit_inner_unit_space_instance = GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpace.from_json(json)
# print the JSON string representation of the object
print(GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpace.to_json())

# convert the object into a dict
get_units_availability_and_pricing_success_response_result_property_units_property_unit_inner_unit_space_dict = get_units_availability_and_pricing_success_response_result_property_units_property_unit_inner_unit_space_instance.to_dict()
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpace from a dict
get_units_availability_and_pricing_success_response_result_property_units_property_unit_inner_unit_space_from_dict = GetUnitsAvailabilityAndPricingSuccessResponseResultPropertyUnitsPropertyUnitInnerUnitSpace.from_dict(get_units_availability_and_pricing_success_response_result_property_units_property_unit_inner_unit_space_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



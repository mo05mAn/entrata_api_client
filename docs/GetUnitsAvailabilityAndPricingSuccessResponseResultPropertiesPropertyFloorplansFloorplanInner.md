# GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the floor plan | 
**unit_count** | **int** | Number of units available for this floor plan | 
**units_available** | **int** | Units currently available for rent | 
**room** | [**List[GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInnerRoomInner]**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInnerRoomInner.md) | List of rooms in the floor plan | 
**square_feet** | [**GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInnerSquareFeet**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInnerSquareFeet.md) |  | 
**market_rent** | [**GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInnerMarketRent**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInnerMarketRent.md) |  | 
**deposit** | [**GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInnerDeposit**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInnerDeposit.md) |  | 

## Example

```python
from openapi_client.models.get_units_availability_and_pricing_success_response_result_properties_property_floorplans_floorplan_inner import GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInner from a JSON string
get_units_availability_and_pricing_success_response_result_properties_property_floorplans_floorplan_inner_instance = GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInner.from_json(json)
# print the JSON string representation of the object
print(GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInner.to_json())

# convert the object into a dict
get_units_availability_and_pricing_success_response_result_properties_property_floorplans_floorplan_inner_dict = get_units_availability_and_pricing_success_response_result_properties_property_floorplans_floorplan_inner_instance.to_dict()
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInner from a dict
get_units_availability_and_pricing_success_response_result_properties_property_floorplans_floorplan_inner_from_dict = GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplansFloorplanInner.from_dict(get_units_availability_and_pricing_success_response_result_properties_property_floorplans_floorplan_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



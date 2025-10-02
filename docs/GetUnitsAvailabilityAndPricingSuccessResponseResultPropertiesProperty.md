# GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesProperty

Details of the property

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | Unique identifier for the property | 
**marketing_name** | **str** | The marketing name of the property | 
**floorplans** | [**GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplans**](GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesPropertyFloorplans.md) |  | 

## Example

```python
from openapi_client.models.get_units_availability_and_pricing_success_response_result_properties_property import GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesProperty from a JSON string
get_units_availability_and_pricing_success_response_result_properties_property_instance = GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesProperty.from_json(json)
# print the JSON string representation of the object
print(GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesProperty.to_json())

# convert the object into a dict
get_units_availability_and_pricing_success_response_result_properties_property_dict = get_units_availability_and_pricing_success_response_result_properties_property_instance.to_dict()
# create an instance of GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesProperty from a dict
get_units_availability_and_pricing_success_response_result_properties_property_from_dict = GetUnitsAvailabilityAndPricingSuccessResponseResultPropertiesProperty.from_dict(get_units_availability_and_pricing_success_response_result_properties_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetUnitsAvailabilityAndPricingMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**floorplan_id** | **int** |   This is an optional field. This field accepts single value. Floorplan Id | [optional] 
**unit_type_id** | **int** | This is an optional field. This field accepts single value. Unit Type Id | [optional] 
**property_unit_id** | **int** | This is an optional field. This field accepts single value. Property Unit Id | [optional] 
**available_units_only** | **int** | This is an optional field. This field accepts single value. If provided as 1 response will contain only available units. And If pr ovided as 0 response will contain all available and unavailable units | [optional] 
**unavailable_units_only** | **int** | This is an optional field. This field accepts single value. If provided value as 1 then will return only unavailable units in the response. | [optional] 
**skip_pricing** | **int** | This is an optional field. This field accepts single value. If provided value as 1 then will not show the rates(default API will r eturn the pricing) | [optional] 
**show_child_properties** | **int** | This is an optional field. This field accepts single value. Shows child properties in result, by default child properties will be included in result. | [optional] 
**include_disabled_floorplans** | **int** | This is an optional field. This field accepts single value. Flag for implementing Disabled Floorplans on result. | [optional] 
**include_disabled_units** | **int** | This is an optional field. This field accepts single value. Flag for implementing Disabled Units on result. | [optional] 
**show_unit_spaces** | **int** | This is an optional field. This field accepts single value. showUnitSpaces | [optional] 
**use_space_configuration** | **int** | This is an optional field. This field accepts single value. Considered if the property has space configuration setup then the rate should return as per space configuration. | [optional] 
**allow_lease_expiration_override** | **int** | This is an optional field. This field accepts single value. If \&quot;1\&quot; is sent then we should override any lease expiration limits aff ecting available units returned/ If \&quot;0\&quot; or node is missing then do cur rent default functionality | [optional] 
**move_in_start_date** | **date** | This is an optional field. This field accepts single value. Desired move in start date for finding unit availability and pricing. | [optional] 
**move_in_end_date** | **date** | This is an optional field. This field accepts single value. Desired move in end date for finding unit availability and pricing. | [optional] 

## Example

```python
from openapi_client.models.get_units_availability_and_pricing_method_params import GetUnitsAvailabilityAndPricingMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitsAvailabilityAndPricingMethodParams from a JSON string
get_units_availability_and_pricing_method_params_instance = GetUnitsAvailabilityAndPricingMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetUnitsAvailabilityAndPricingMethodParams.to_json())

# convert the object into a dict
get_units_availability_and_pricing_method_params_dict = get_units_availability_and_pricing_method_params_instance.to_dict()
# create an instance of GetUnitsAvailabilityAndPricingMethodParams from a dict
get_units_availability_and_pricing_method_params_from_dict = GetUnitsAvailabilityAndPricingMethodParams.from_dict(get_units_availability_and_pricing_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



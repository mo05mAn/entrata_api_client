# GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnitsUnitRatesRateAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_code_id** | **str** | Unique identifier for the charge code | [optional] 
**ar_code_type_id** | **str** | Type of the charge | [optional] 
**charge_type_id** | **str** | Charge type ID | [optional] 
**amount** | **str** | The amount associated with the rate | [optional] 
**is_published** | **str** | Indicates if the rate is published | [optional] 
**is_active** | **str** | Indicates if the rate is active | [optional] 
**lease_term_id** | **str** | The lease term ID | [optional] 
**lease_start_window_id** | **str** | The lease start window ID | [optional] 

## Example

```python
from openapi_client.models.get_amenities_success_response_result_amenities_unit_amenities_amenity_units_unit_rates_rate_attributes import GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnitsUnitRatesRateAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnitsUnitRatesRateAttributes from a JSON string
get_amenities_success_response_result_amenities_unit_amenities_amenity_units_unit_rates_rate_attributes_instance = GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnitsUnitRatesRateAttributes.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnitsUnitRatesRateAttributes.to_json())

# convert the object into a dict
get_amenities_success_response_result_amenities_unit_amenities_amenity_units_unit_rates_rate_attributes_dict = get_amenities_success_response_result_amenities_unit_amenities_amenity_units_unit_rates_rate_attributes_instance.to_dict()
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnitsUnitRatesRateAttributes from a dict
get_amenities_success_response_result_amenities_unit_amenities_amenity_units_unit_rates_rate_attributes_from_dict = GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnitsUnitRatesRateAttributes.from_dict(get_amenities_success_response_result_amenities_unit_amenities_amenity_units_unit_rates_rate_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



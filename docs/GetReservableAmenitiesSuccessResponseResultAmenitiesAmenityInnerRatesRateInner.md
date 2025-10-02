# GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRatesRateInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_code_id** | **str** | AR code ID for the rate | 
**ar_code_type_id** | **str** | AR code type ID | 
**charge_type_id** | **str** | Charge type ID | 
**amount** | **str** | Amount for the rate | 
**active** | **str** | Whether the rate is active | 
**is_publish** | **str** | Indicates whether the rate is published | 

## Example

```python
from openapi_client.models.get_reservable_amenities_success_response_result_amenities_amenity_inner_rates_rate_inner import GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRatesRateInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRatesRateInner from a JSON string
get_reservable_amenities_success_response_result_amenities_amenity_inner_rates_rate_inner_instance = GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRatesRateInner.from_json(json)
# print the JSON string representation of the object
print(GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRatesRateInner.to_json())

# convert the object into a dict
get_reservable_amenities_success_response_result_amenities_amenity_inner_rates_rate_inner_dict = get_reservable_amenities_success_response_result_amenities_amenity_inner_rates_rate_inner_instance.to_dict()
# create an instance of GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRatesRateInner from a dict
get_reservable_amenities_success_response_result_amenities_amenity_inner_rates_rate_inner_from_dict = GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRatesRateInner.from_dict(get_reservable_amenities_success_response_result_amenities_amenity_inner_rates_rate_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



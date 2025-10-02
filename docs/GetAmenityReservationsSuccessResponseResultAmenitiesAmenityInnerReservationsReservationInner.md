# GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the reservation | 
**resident** | **str** | Name of the resident who made the reservation | 
**lease_id** | **str** | ID of the lease associated with the reservation | [optional] 
**unit_id** | **str** | ID of the unit where the amenity is reserved | [optional] 
**unit_number** | **str** | Unit number where the amenity is reserved | [optional] 
**reservation_date** | **str** | Date of the reservation | 
**reserve_by_day** | **str** | Indicates whether the reservation is by day | [optional] 
**reservation_start_time** | **str** | Start time of the reservation | 
**reservation_end_time** | **str** | End time of the reservation | 
**status_type_id** | **str** | ID representing the status type | [optional] 
**status** | **str** | Status of the reservation | 

## Example

```python
from entrata_api_client.models.get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_reservation_inner import GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner from a JSON string
get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_reservation_inner_instance = GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner.from_json(json)
# print the JSON string representation of the object
print(GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner.to_json())

# convert the object into a dict
get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_reservation_inner_dict = get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_reservation_inner_instance.to_dict()
# create an instance of GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner from a dict
get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_reservation_inner_from_dict = GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner.from_dict(get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_reservation_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



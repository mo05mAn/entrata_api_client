# GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations

Reservations for the amenity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reservation** | [**List[GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner]**](GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservationsReservationInner.md) | List of reservations for the amenity | [optional] 

## Example

```python
from entrata_api_client.models.get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations import GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations from a JSON string
get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_instance = GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations.from_json(json)
# print the JSON string representation of the object
print(GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations.to_json())

# convert the object into a dict
get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_dict = get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_instance.to_dict()
# create an instance of GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations from a dict
get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_from_dict = GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations.from_dict(get_amenity_reservations_success_response_result_amenities_amenity_inner_reservations_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



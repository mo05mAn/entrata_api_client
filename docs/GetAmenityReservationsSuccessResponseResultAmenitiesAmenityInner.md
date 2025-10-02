# GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the amenity | 
**name** | **str** | Name of the amenity | 
**description** | **str** | Description of the amenity | 
**is_published** | **str** | Indicates if the amenity is published | 
**reservations** | [**GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations**](GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInnerReservations.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_amenity_reservations_success_response_result_amenities_amenity_inner import GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInner from a JSON string
get_amenity_reservations_success_response_result_amenities_amenity_inner_instance = GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInner.from_json(json)
# print the JSON string representation of the object
print(GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInner.to_json())

# convert the object into a dict
get_amenity_reservations_success_response_result_amenities_amenity_inner_dict = get_amenity_reservations_success_response_result_amenities_amenity_inner_instance.to_dict()
# create an instance of GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInner from a dict
get_amenity_reservations_success_response_result_amenities_amenity_inner_from_dict = GetAmenityReservationsSuccessResponseResultAmenitiesAmenityInner.from_dict(get_amenity_reservations_success_response_result_amenities_amenity_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



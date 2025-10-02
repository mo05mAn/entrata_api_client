# GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | ID of the amenity | 
**name** | **str** | Name of the amenity | 
**description** | **str** | Description of the amenity | [optional] 
**reserved_by_day** | **str** | Indicates whether the amenity is reserved by day | 
**block_hours_by_day** | **str** | Indicates how many hours per day the amenity is blocked | 
**block_days** | [**GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerBlockDays**](GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerBlockDays.md) |  | [optional] 
**max_reservation_days** | **str** | Maximum number of days in advance a resident can reserve the amenity | 
**max_hours** | **str** | Maximum number of hours that can be reserved for the amenity | 
**is_approval_required** | **str** | Whether approval is required for reserving the amenity | 
**is_resident_visible** | **str** | Indicates whether the amenity is visible to residents | 
**is_allow_future_resident** | **str** | Indicates whether future residents are allowed to reserve the amenity | 
**rates** | [**GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRates**](GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInnerRates.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_reservable_amenities_success_response_result_amenities_amenity_inner import GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInner from a JSON string
get_reservable_amenities_success_response_result_amenities_amenity_inner_instance = GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInner.from_json(json)
# print the JSON string representation of the object
print(GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInner.to_json())

# convert the object into a dict
get_reservable_amenities_success_response_result_amenities_amenity_inner_dict = get_reservable_amenities_success_response_result_amenities_amenity_inner_instance.to_dict()
# create an instance of GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInner from a dict
get_reservable_amenities_success_response_result_amenities_amenity_inner_from_dict = GetReservableAmenitiesSuccessResponseResultAmenitiesAmenityInner.from_dict(get_reservable_amenities_success_response_result_amenities_amenity_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



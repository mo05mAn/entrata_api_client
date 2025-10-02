# GetAmenityReservationsSuccessResponseResult

The result containing amenities details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amenities** | [**GetAmenityReservationsSuccessResponseResultAmenities**](GetAmenityReservationsSuccessResponseResultAmenities.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_amenity_reservations_success_response_result import GetAmenityReservationsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenityReservationsSuccessResponseResult from a JSON string
get_amenity_reservations_success_response_result_instance = GetAmenityReservationsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetAmenityReservationsSuccessResponseResult.to_json())

# convert the object into a dict
get_amenity_reservations_success_response_result_dict = get_amenity_reservations_success_response_result_instance.to_dict()
# create an instance of GetAmenityReservationsSuccessResponseResult from a dict
get_amenity_reservations_success_response_result_from_dict = GetAmenityReservationsSuccessResponseResult.from_dict(get_amenity_reservations_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



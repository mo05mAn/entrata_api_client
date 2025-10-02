# GetAmenityReservationsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Success response code | 
**result** | [**GetAmenityReservationsSuccessResponseResult**](GetAmenityReservationsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_amenity_reservations_success_response import GetAmenityReservationsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenityReservationsSuccessResponse from a JSON string
get_amenity_reservations_success_response_instance = GetAmenityReservationsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetAmenityReservationsSuccessResponse.to_json())

# convert the object into a dict
get_amenity_reservations_success_response_dict = get_amenity_reservations_success_response_instance.to_dict()
# create an instance of GetAmenityReservationsSuccessResponse from a dict
get_amenity_reservations_success_response_from_dict = GetAmenityReservationsSuccessResponse.from_dict(get_amenity_reservations_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetAmenityReservations


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetAmenityReservationsMethod**](GetAmenityReservationsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_amenity_reservations import GetAmenityReservations

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenityReservations from a JSON string
get_amenity_reservations_instance = GetAmenityReservations.from_json(json)
# print the JSON string representation of the object
print(GetAmenityReservations.to_json())

# convert the object into a dict
get_amenity_reservations_dict = get_amenity_reservations_instance.to_dict()
# create an instance of GetAmenityReservations from a dict
get_amenity_reservations_from_dict = GetAmenityReservations.from_dict(get_amenity_reservations_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



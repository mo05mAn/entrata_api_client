# GetAmenityReservationsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**amenity_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**amenity_reservation_status_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 

## Example

```python
from openapi_client.models.get_amenity_reservations_method_params import GetAmenityReservationsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenityReservationsMethodParams from a JSON string
get_amenity_reservations_method_params_instance = GetAmenityReservationsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetAmenityReservationsMethodParams.to_json())

# convert the object into a dict
get_amenity_reservations_method_params_dict = get_amenity_reservations_method_params_instance.to_dict()
# create an instance of GetAmenityReservationsMethodParams from a dict
get_amenity_reservations_method_params_from_dict = GetAmenityReservationsMethodParams.from_dict(get_amenity_reservations_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



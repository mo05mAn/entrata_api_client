# GetAmenityReservationsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetAmenityReservationsMethodParams**](GetAmenityReservationsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_amenity_reservations_method import GetAmenityReservationsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenityReservationsMethod from a JSON string
get_amenity_reservations_method_instance = GetAmenityReservationsMethod.from_json(json)
# print the JSON string representation of the object
print(GetAmenityReservationsMethod.to_json())

# convert the object into a dict
get_amenity_reservations_method_dict = get_amenity_reservations_method_instance.to_dict()
# create an instance of GetAmenityReservationsMethod from a dict
get_amenity_reservations_method_from_dict = GetAmenityReservationsMethod.from_dict(get_amenity_reservations_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



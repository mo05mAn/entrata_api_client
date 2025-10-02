# GetReservableAmenities


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetReservableAmenitiesMethod**](GetReservableAmenitiesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_reservable_amenities import GetReservableAmenities

# TODO update the JSON string below
json = "{}"
# create an instance of GetReservableAmenities from a JSON string
get_reservable_amenities_instance = GetReservableAmenities.from_json(json)
# print the JSON string representation of the object
print(GetReservableAmenities.to_json())

# convert the object into a dict
get_reservable_amenities_dict = get_reservable_amenities_instance.to_dict()
# create an instance of GetReservableAmenities from a dict
get_reservable_amenities_from_dict = GetReservableAmenities.from_dict(get_reservable_amenities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



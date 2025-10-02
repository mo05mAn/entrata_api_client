# GetReservableAmenitiesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**amenity_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 

## Example

```python
from entrata_api_client.models.get_reservable_amenities_method_params import GetReservableAmenitiesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetReservableAmenitiesMethodParams from a JSON string
get_reservable_amenities_method_params_instance = GetReservableAmenitiesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetReservableAmenitiesMethodParams.to_json())

# convert the object into a dict
get_reservable_amenities_method_params_dict = get_reservable_amenities_method_params_instance.to_dict()
# create an instance of GetReservableAmenitiesMethodParams from a dict
get_reservable_amenities_method_params_from_dict = GetReservableAmenitiesMethodParams.from_dict(get_reservable_amenities_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



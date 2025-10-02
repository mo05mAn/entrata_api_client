# GetReservableAmenitiesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetReservableAmenitiesMethodParams**](GetReservableAmenitiesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_reservable_amenities_method import GetReservableAmenitiesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetReservableAmenitiesMethod from a JSON string
get_reservable_amenities_method_instance = GetReservableAmenitiesMethod.from_json(json)
# print the JSON string representation of the object
print(GetReservableAmenitiesMethod.to_json())

# convert the object into a dict
get_reservable_amenities_method_dict = get_reservable_amenities_method_instance.to_dict()
# create an instance of GetReservableAmenitiesMethod from a dict
get_reservable_amenities_method_from_dict = GetReservableAmenitiesMethod.from_dict(get_reservable_amenities_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetReservableAmenitiesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amenities** | [**GetReservableAmenitiesSuccessResponseResultAmenities**](GetReservableAmenitiesSuccessResponseResultAmenities.md) |  | 

## Example

```python
from entrata_api_client.models.get_reservable_amenities_success_response_result import GetReservableAmenitiesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetReservableAmenitiesSuccessResponseResult from a JSON string
get_reservable_amenities_success_response_result_instance = GetReservableAmenitiesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetReservableAmenitiesSuccessResponseResult.to_json())

# convert the object into a dict
get_reservable_amenities_success_response_result_dict = get_reservable_amenities_success_response_result_instance.to_dict()
# create an instance of GetReservableAmenitiesSuccessResponseResult from a dict
get_reservable_amenities_success_response_result_from_dict = GetReservableAmenitiesSuccessResponseResult.from_dict(get_reservable_amenities_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



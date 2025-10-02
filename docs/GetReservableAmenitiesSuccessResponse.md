# GetReservableAmenitiesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**GetReservableAmenitiesSuccessResponseResult**](GetReservableAmenitiesSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_reservable_amenities_success_response import GetReservableAmenitiesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetReservableAmenitiesSuccessResponse from a JSON string
get_reservable_amenities_success_response_instance = GetReservableAmenitiesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetReservableAmenitiesSuccessResponse.to_json())

# convert the object into a dict
get_reservable_amenities_success_response_dict = get_reservable_amenities_success_response_instance.to_dict()
# create an instance of GetReservableAmenitiesSuccessResponse from a dict
get_reservable_amenities_success_response_from_dict = GetReservableAmenitiesSuccessResponse.from_dict(get_reservable_amenities_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



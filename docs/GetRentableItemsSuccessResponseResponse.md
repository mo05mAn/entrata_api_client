# GetRentableItemsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **int** | Unique identifier for the request | 
**result** | [**GetRentableItemsSuccessResponseResponseResult**](GetRentableItemsSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_rentable_items_success_response_response import GetRentableItemsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentableItemsSuccessResponseResponse from a JSON string
get_rentable_items_success_response_response_instance = GetRentableItemsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetRentableItemsSuccessResponseResponse.to_json())

# convert the object into a dict
get_rentable_items_success_response_response_dict = get_rentable_items_success_response_response_instance.to_dict()
# create an instance of GetRentableItemsSuccessResponseResponse from a dict
get_rentable_items_success_response_response_from_dict = GetRentableItemsSuccessResponseResponse.from_dict(get_rentable_items_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



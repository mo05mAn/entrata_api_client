# GetRentableItemsSuccessResponseResponseResult

Contains rentable item types, items, and charge details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rentable_item_types** | [**GetRentableItemsSuccessResponseResponseResultRentableItemTypes**](GetRentableItemsSuccessResponseResponseResultRentableItemTypes.md) |  | 

## Example

```python
from openapi_client.models.get_rentable_items_success_response_response_result import GetRentableItemsSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentableItemsSuccessResponseResponseResult from a JSON string
get_rentable_items_success_response_response_result_instance = GetRentableItemsSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetRentableItemsSuccessResponseResponseResult.to_json())

# convert the object into a dict
get_rentable_items_success_response_response_result_dict = get_rentable_items_success_response_response_result_instance.to_dict()
# create an instance of GetRentableItemsSuccessResponseResponseResult from a dict
get_rentable_items_success_response_response_result_from_dict = GetRentableItemsSuccessResponseResponseResult.from_dict(get_rentable_items_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



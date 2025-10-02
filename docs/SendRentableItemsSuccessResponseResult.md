# SendRentableItemsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rentable_item_types** | [**SendRentableItemsSuccessResponseResultRentableItemTypes**](SendRentableItemsSuccessResponseResultRentableItemTypes.md) |  | 

## Example

```python
from openapi_client.models.send_rentable_items_success_response_result import SendRentableItemsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentableItemsSuccessResponseResult from a JSON string
send_rentable_items_success_response_result_instance = SendRentableItemsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendRentableItemsSuccessResponseResult.to_json())

# convert the object into a dict
send_rentable_items_success_response_result_dict = send_rentable_items_success_response_result_instance.to_dict()
# create an instance of SendRentableItemsSuccessResponseResult from a dict
send_rentable_items_success_response_result_from_dict = SendRentableItemsSuccessResponseResult.from_dict(send_rentable_items_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# SendRentableItemsSuccessResponseResultRentableItemTypesRentableItemTypeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Node identifier for the rentable item type | 
**rentable_item_type_id** | **int** | Unique identifier for the rentable item type | 
**rentable_item_ids** | **str** | Comma-separated list of rentable item IDs associated with this type | 
**status** | **str** | Status of the rentable item type insertion | 
**message** | **str** | Message related to the rentable item type insertion | 

## Example

```python
from openapi_client.models.send_rentable_items_success_response_result_rentable_item_types_rentable_item_type_inner import SendRentableItemsSuccessResponseResultRentableItemTypesRentableItemTypeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendRentableItemsSuccessResponseResultRentableItemTypesRentableItemTypeInner from a JSON string
send_rentable_items_success_response_result_rentable_item_types_rentable_item_type_inner_instance = SendRentableItemsSuccessResponseResultRentableItemTypesRentableItemTypeInner.from_json(json)
# print the JSON string representation of the object
print(SendRentableItemsSuccessResponseResultRentableItemTypesRentableItemTypeInner.to_json())

# convert the object into a dict
send_rentable_items_success_response_result_rentable_item_types_rentable_item_type_inner_dict = send_rentable_items_success_response_result_rentable_item_types_rentable_item_type_inner_instance.to_dict()
# create an instance of SendRentableItemsSuccessResponseResultRentableItemTypesRentableItemTypeInner from a dict
send_rentable_items_success_response_result_rentable_item_types_rentable_item_type_inner_from_dict = SendRentableItemsSuccessResponseResultRentableItemTypesRentableItemTypeInner.from_dict(send_rentable_items_success_response_result_rentable_item_types_rentable_item_type_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



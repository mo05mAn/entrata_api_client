# GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItem


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID of the rentable item | 
**name** | **str** | Name of the rentable item | 
**reservation_start_date** | **str** | Start date for reservations | 
**reservation_end_date** | **str** | End date for reservations | 
**hold_until** | **str** | Hold until date for the item | 
**rents** | [**GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItemRents**](GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItemRents.md) |  | 
**deposits** | [**GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItemDeposits**](GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItemDeposits.md) |  | 
**description** | **str** | Description of the rentable item | 

## Example

```python
from openapi_client.models.get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_rentable_items_rentable_item import GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItem

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItem from a JSON string
get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_rentable_items_rentable_item_instance = GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItem.from_json(json)
# print the JSON string representation of the object
print(GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItem.to_json())

# convert the object into a dict
get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_rentable_items_rentable_item_dict = get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_rentable_items_rentable_item_instance.to_dict()
# create an instance of GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItem from a dict
get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_rentable_items_rentable_item_from_dict = GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItemsRentableItem.from_dict(get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_rentable_items_rentable_item_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



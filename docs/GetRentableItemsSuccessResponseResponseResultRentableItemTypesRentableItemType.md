# GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID of the rentable item type | 
**name** | **str** | Name of the rentable item type | 
**description** | **str** | Description of the rentable item type | 
**rents** | [**GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRents**](GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRents.md) |  | 
**deposits** | [**GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeDeposits**](GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeDeposits.md) |  | 
**rentable_items** | [**GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItems**](GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemTypeRentableItems.md) |  | 

## Example

```python
from entrata_api_client.models.get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type import GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemType

# TODO update the JSON string below
json = "{}"
# create an instance of GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemType from a JSON string
get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_instance = GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemType.from_json(json)
# print the JSON string representation of the object
print(GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemType.to_json())

# convert the object into a dict
get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_dict = get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_instance.to_dict()
# create an instance of GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemType from a dict
get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_from_dict = GetRentableItemsSuccessResponseResponseResultRentableItemTypesRentableItemType.from_dict(get_rentable_items_success_response_response_result_rentable_item_types_rentable_item_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



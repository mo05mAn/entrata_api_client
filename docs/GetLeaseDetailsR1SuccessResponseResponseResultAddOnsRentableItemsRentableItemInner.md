# GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItemsRentableItemInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**add_on_type** | **str** | Type of the rentable item. | 
**add_on_category** | **str** | Category of the rentable item. | 
**add_on_group** | **str** | Group the rentable item belongs to. | [optional] 
**add_on_name** | **str** | Name of the rentable item. | 
**lease_status_type** | **str** | Lease status of the rentable item. | 
**start_date** | **str** | Start date of the rentable item. | 
**end_date** | **str** | End date of the rentable item. | 
**agent** | **str** | Agent responsible for the rentable item. | 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_success_response_response_result_add_ons_rentable_items_rentable_item_inner import GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItemsRentableItemInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItemsRentableItemInner from a JSON string
get_lease_details_r1_success_response_response_result_add_ons_rentable_items_rentable_item_inner_instance = GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItemsRentableItemInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItemsRentableItemInner.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_add_ons_rentable_items_rentable_item_inner_dict = get_lease_details_r1_success_response_response_result_add_ons_rentable_items_rentable_item_inner_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItemsRentableItemInner from a dict
get_lease_details_r1_success_response_response_result_add_ons_rentable_items_rentable_item_inner_from_dict = GetLeaseDetailsR1SuccessResponseResponseResultAddOnsRentableItemsRentableItemInner.from_dict(get_lease_details_r1_success_response_response_result_add_ons_rentable_items_rentable_item_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOnsRentableItemsRentableItem


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**add_on_id** | **int** | Unique identifier for the add-on. | 
**add_on_type** | **str** | Type of the rentable item. | 
**add_on_category** | **str** | Category of the rentable item. | 
**add_on_group** | **str** | Group of the rentable item. | 
**add_on_name** | **str** | Name of the rentable item. | 
**lease_status_type** | **str** | Status of the lease for this item. | 
**start_date** | **str** | Start date of the add-on. | 
**end_date** | **str** | End date of the add-on. | 
**agent** | **str** | Agent responsible for the add-on. | 

## Example

```python
from openapi_client.models.get_lease_details_r2_success_response_result_leases_lease_add_ons_rentable_items_rentable_item import GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOnsRentableItemsRentableItem

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOnsRentableItemsRentableItem from a JSON string
get_lease_details_r2_success_response_result_leases_lease_add_ons_rentable_items_rentable_item_instance = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOnsRentableItemsRentableItem.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOnsRentableItemsRentableItem.to_json())

# convert the object into a dict
get_lease_details_r2_success_response_result_leases_lease_add_ons_rentable_items_rentable_item_dict = get_lease_details_r2_success_response_result_leases_lease_add_ons_rentable_items_rentable_item_instance.to_dict()
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOnsRentableItemsRentableItem from a dict
get_lease_details_r2_success_response_result_leases_lease_add_ons_rentable_items_rentable_item_from_dict = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOnsRentableItemsRentableItem.from_dict(get_lease_details_r2_success_response_result_leases_lease_add_ons_rentable_items_rentable_item_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItemsAssignableItemInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**add_on_type** | **str** | Type of the add-on item. | 
**add_on_category** | **str** | Category of the add-on. | 
**add_on_group** | **str** | Group the add-on belongs to. | [optional] 
**add_on_name** | **str** | Name of the add-on item. | 
**lease_status_type** | **str** | Lease status of the add-on item. | 
**start_date** | **str** | Start date of the add-on. | 
**end_date** | **str** | End date of the add-on. | 
**agent** | **str** | Agent responsible for the add-on. | 

## Example

```python
from openapi_client.models.get_lease_details_r1_success_response_response_result_add_ons_assignable_items_assignable_item_inner import GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItemsAssignableItemInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItemsAssignableItemInner from a JSON string
get_lease_details_r1_success_response_response_result_add_ons_assignable_items_assignable_item_inner_instance = GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItemsAssignableItemInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItemsAssignableItemInner.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_add_ons_assignable_items_assignable_item_inner_dict = get_lease_details_r1_success_response_response_result_add_ons_assignable_items_assignable_item_inner_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItemsAssignableItemInner from a dict
get_lease_details_r1_success_response_response_result_add_ons_assignable_items_assignable_item_inner_from_dict = GetLeaseDetailsR1SuccessResponseResponseResultAddOnsAssignableItemsAssignableItemInner.from_dict(get_lease_details_r1_success_response_response_result_add_ons_assignable_items_assignable_item_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



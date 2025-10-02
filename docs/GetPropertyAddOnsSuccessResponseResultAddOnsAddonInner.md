# GetPropertyAddOnsSuccessResponseResultAddOnsAddonInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier for the add-on | 
**name** | **str** | Name of the add-on | 
**add_on_type_id** | **str** | Identifier for the add-on type | 
**add_on_category_id** | **int** | Identifier for the add-on category | 
**add_on_group_id** | **int** | Identifier for the add-on group | 
**is_inventory** | **int** | Indicates if the add-on is part of inventory (1 &#x3D; Yes, 0 &#x3D; No) | 
**add_on_available_on** | **str** | Date when the add-on becomes available | 
**is_web_visible** | **int** | Indicates if the add-on is visible on the web (1 &#x3D; Visible, 0 &#x3D; Not Visible) | 
**availability** | **str** | Availability status of the add-on | 
**reservation_start_date** | **str** | Start date for reservation | 
**reservation_end_date** | **str** | End date for reservation | 
**hold_until_date** | **str** | Date until which the add-on is held | 
**rates** | [**GetPropertyAddOnsSuccessResponseResultAddOnsAddonInnerRates**](GetPropertyAddOnsSuccessResponseResultAddOnsAddonInnerRates.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_property_add_ons_success_response_result_add_ons_addon_inner import GetPropertyAddOnsSuccessResponseResultAddOnsAddonInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAddOnsSuccessResponseResultAddOnsAddonInner from a JSON string
get_property_add_ons_success_response_result_add_ons_addon_inner_instance = GetPropertyAddOnsSuccessResponseResultAddOnsAddonInner.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAddOnsSuccessResponseResultAddOnsAddonInner.to_json())

# convert the object into a dict
get_property_add_ons_success_response_result_add_ons_addon_inner_dict = get_property_add_ons_success_response_result_add_ons_addon_inner_instance.to_dict()
# create an instance of GetPropertyAddOnsSuccessResponseResultAddOnsAddonInner from a dict
get_property_add_ons_success_response_result_add_ons_addon_inner_from_dict = GetPropertyAddOnsSuccessResponseResultAddOnsAddonInner.from_dict(get_property_add_ons_success_response_result_add_ons_addon_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# UpdateSpecialGroupMethodParamsSpecialGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**special_group_id** | **str** | Required. The ID of the special group to update | 
**special_group_name** | **str** | Required. Name of the special group | 
**internal_description** | **str** | Optional. Internal description not visible to residents | [optional] 
**floor_plan_ids** | **str** | Optional. Comma separated floor plan IDs. | [optional] 
**unit_type_ids** | **str** | Optional. Comma separated unit type IDs. | [optional] 
**unit_space_ids** | **str** | Optional. Comma separated unit space IDs. | [optional] 
**is_active** | **str** | Optional. Determines if special is eligible to be used | [optional] 
**is_web_visible** | **str** | Optional. Determines if special will be shown in advertising | [optional] 
**start_date** | **str** | Optional. Date special will be advertised from | [optional] 
**end_date** | **str** | Optional. Date special will be advertised to | [optional] 
**hide_end_date** | **str** | Optional. Determines if special end date will be advertised | [optional] 
**marketing_description** | **str** | Optional. Description shown to residents | [optional] 
**terms_and_conditions** | **str** | Optional. Terms and conditions for the specials | [optional] 
**is_advertised** | **str** | Optional. Determines if special is manual only | [optional] 
**move_in_date_from** | **str** | Optional. Start of move-in date range | [optional] 
**move_in_date_to** | **str** | Optional. End of move-in date range | [optional] 
**renewal_start_date_from** | **str** | Optional. Start of renewal date range | [optional] 
**renewal_start_date_to** | **str** | Optional. End of renewal date range | [optional] 
**limit_quantity** | **str** | Optional. Allows setting limits on specials | [optional] 
**quantity_budgeted** | **str** | Optional. Number of specials to be given | [optional] 
**coupon_code** | **str** | Optional. Promotional code for special | [optional] 
**lead_source_id** | **str** | Optional. Source ID for promo code | [optional] 
**incentive_limit** | **str** | Optional. Number of incentives resident can receive | [optional] 
**is_selectable** | **str** | Optional. If specials incentive count matches limit | [optional] 
**is_delete** | **int** | Optional. pass this field if only wants to delete the special group. otherwise do not pass this field. | [optional] 
**lease_term_details** | [**List[UpdateSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner]**](UpdateSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner.md) |  | [optional] 
**special_recipient_details** | [**UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails**](UpdateSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails.md) |  | [optional] 
**special_group_space_configuration_ids** | **str** | Optional. Comma-separated space configuration IDs | [optional] 
**specials** | [**List[UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner]**](UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner.md) |  | [optional] 

## Example

```python
from openapi_client.models.update_special_group_method_params_special_group import UpdateSpecialGroupMethodParamsSpecialGroup

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateSpecialGroupMethodParamsSpecialGroup from a JSON string
update_special_group_method_params_special_group_instance = UpdateSpecialGroupMethodParamsSpecialGroup.from_json(json)
# print the JSON string representation of the object
print(UpdateSpecialGroupMethodParamsSpecialGroup.to_json())

# convert the object into a dict
update_special_group_method_params_special_group_dict = update_special_group_method_params_special_group_instance.to_dict()
# create an instance of UpdateSpecialGroupMethodParamsSpecialGroup from a dict
update_special_group_method_params_special_group_from_dict = UpdateSpecialGroupMethodParamsSpecialGroup.from_dict(update_special_group_method_params_special_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# SendSpecialGroupMethodParamsSpecialGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**special_group_name** | **str** | This is a required field. This accepts the Special Group name. | 
**internal_description** | **str** | This is an optional field. Internal description not visible to residents. | [optional] 
**floor_plan_ids** | **str** | This is an optional field. Comma separated floor plan IDs. | [optional] 
**unit_type_ids** | **str** | This is an optional field. Comma separated unit type IDs. | [optional] 
**unit_space_ids** | **str** | This is an optional field. Comma separated unit space IDs. | [optional] 
**is_active** | **str** | This is an optional field. Determines if special is eligible to be used. | [optional] 
**is_web_visible** | **str** | This is an optional field. Determines if special will be shown in advertising. | [optional] 
**start_date** | **str** | This is an optional field. Date special will be advertised from. | [optional] 
**end_date** | **str** | This is an optional field. Date special will be advertised to. | [optional] 
**hide_end_date** | **str** | This is an optional field. Determines if special end date will be advertised. | [optional] 
**marketing_description** | **str** | This is an optional field. Description shown to residents. | [optional] 
**terms_and_conditions** | **str** | This is an optional field. Terms and conditions for specials. | [optional] 
**is_advertised** | **str** | This is an optional field. Determines if special is manual only. | [optional] 
**move_in_date_from** | **str** | This is an optional field. Start of move-in date range. | [optional] 
**move_in_date_to** | **str** | This is an optional field. End of move-in date range. | [optional] 
**renewal_start_date_from** | **str** | This is an optional field. Start of renewal date range. | [optional] 
**renewal_start_date_to** | **str** | This is an optional field. End of renewal date range. | [optional] 
**limit_quantity** | **str** | This is an optional field. Allows setting limits on specials. | [optional] 
**quantity_budgeted** | **str** | This is an optional field. Limits number of specials given. | [optional] 
**coupon_code** | **str** | This is an optional field. Promotional code required during application. | [optional] 
**lead_source_id** | **str** | This is an optional field. Source of promo code. | [optional] 
**incentive_limit** | **str** | This is an optional field. Number of incentives resident receives. | [optional] 
**is_selectable** | **str** | This is an optional field. If specials incentive count matches limit. | [optional] 
**lease_term_details** | [**List[SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner]**](SendSpecialGroupMethodParamsSpecialGroupLeaseTermDetailsInner.md) |  | [optional] 
**special_recipient_details** | [**SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails**](SendSpecialGroupMethodParamsSpecialGroupSpecialRecipientDetails.md) |  | [optional] 
**special_group_space_configuration_ids** | **str** | This is an optional field. Comma separated space configuration IDs. | [optional] 
**specials** | [**List[SendSpecialGroupMethodParamsSpecialGroupSpecialsInner]**](SendSpecialGroupMethodParamsSpecialGroupSpecialsInner.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_special_group_method_params_special_group import SendSpecialGroupMethodParamsSpecialGroup

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupMethodParamsSpecialGroup from a JSON string
send_special_group_method_params_special_group_instance = SendSpecialGroupMethodParamsSpecialGroup.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupMethodParamsSpecialGroup.to_json())

# convert the object into a dict
send_special_group_method_params_special_group_dict = send_special_group_method_params_special_group_instance.to_dict()
# create an instance of SendSpecialGroupMethodParamsSpecialGroup from a dict
send_special_group_method_params_special_group_from_dict = SendSpecialGroupMethodParamsSpecialGroup.from_dict(send_special_group_method_params_special_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



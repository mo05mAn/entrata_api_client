# GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**special_group_id** | **str** |  | [optional] 
**special_group_name** | **str** |  | [optional] 
**quantity_budgeted** | **str** |  | [optional] 
**quantity_remaining** | **str** |  | [optional] 
**is_active** | **str** |  | [optional] 
**is_advertised** | **str** |  | [optional] 
**show_on_website** | **str** |  | [optional] 
**start_date** | **str** |  | [optional] 
**end_date** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**internal_description** | **str** |  | [optional] 
**coupon_code** | **str** |  | [optional] 
**special_recipient_details** | [**List[GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerSpecialRecipientDetailsInner]**](GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerSpecialRecipientDetailsInner.md) |  | [optional] 
**limit_quantity** | **str** |  | [optional] 
**terms_and_conditions** | **str** |  | [optional] 
**lead_source_details** | [**List[GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerLeadSourceDetailsInner]**](GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerLeadSourceDetailsInner.md) |  | [optional] 
**renewal_lease_start_date_range** | **str** |  | [optional] 
**prospect_lease_start_date_range** | **str** |  | [optional] 
**space_configuration_details** | [**List[GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerSpaceConfigurationDetailsInner]**](GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerSpaceConfigurationDetailsInner.md) |  | [optional] 
**incentive_limit** | **str** |  | [optional] 
**is_selectable** | **str** |  | [optional] 
**associations** | [**GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerAssociations**](GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerAssociations.md) |  | [optional] 
**special_recipient_trigger_type_details** | [**List[GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerSpecialRecipientTriggerTypeDetailsInner]**](GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerSpecialRecipientTriggerTypeDetailsInner.md) |  | [optional] 
**lease_term_details** | [**List[GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerLeaseTermDetailsInner]**](GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerLeaseTermDetailsInner.md) |  | [optional] 
**specials** | [**List[GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerSpecialsInner]**](GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInnerSpecialsInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_specials_r4_success_response_response_result_special_groups_inner import GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInner from a JSON string
get_specials_r4_success_response_response_result_special_groups_inner_instance = GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInner.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInner.to_json())

# convert the object into a dict
get_specials_r4_success_response_response_result_special_groups_inner_dict = get_specials_r4_success_response_response_result_special_groups_inner_instance.to_dict()
# create an instance of GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInner from a dict
get_specials_r4_success_response_response_result_special_groups_inner_from_dict = GetSpecialsR4SuccessResponseResponseResultSpecialGroupsInner.from_dict(get_specials_r4_success_response_response_result_special_groups_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



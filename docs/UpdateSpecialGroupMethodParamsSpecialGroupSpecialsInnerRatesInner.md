# UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_code_id** | **str** | Optional. AR code identifier | [optional] 
**ar_trigger_id** | **str** | Optional. AR trigger identifier | [optional] 
**ar_code_type_id** | **str** | Optional. AR code type identifier | [optional] 
**customer_relationship_id** | **str** | Optional. Customer relationship identifier | [optional] 
**lease_term_id** | **str** | Optional. Lease term identifier | [optional] 
**lease_term_month** | **str** | Optional. Integer representation of lease term | [optional] 
**lease_start_window_id** | **str** | Optional. Lease start window identifier | [optional] 
**window_start_date** | **str** | Optional. Start date for lease window | [optional] 
**window_end_date** | **str** | Optional. End date for lease window | [optional] 
**effective_date** | **str** | Optional. Date rate becomes effective | [optional] 
**ar_formula_id** | **str** | Optional. AR formula identifier | [optional] 
**rate_interval_start** | **str** | Optional. Month when special starts | [optional] 
**rate_amount** | **str** | Optional. Rate amount | [optional] 
**rate_increase_increment** | **str** | Optional. Increment for percent base formula | [optional] 
**ar_formula_reference_id** | **str** | Optional. Additional formula information | [optional] 
**space_configuration_id** | **str** | Optional. Space configuration identifier | [optional] 
**show_in_entrata** | **str** | Optional. Display within Entrata | [optional] 
**show_on_website** | **str** | Optional. Display on website | [optional] 

## Example

```python
from entrata_api_client.models.update_special_group_method_params_special_group_specials_inner_rates_inner import UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner from a JSON string
update_special_group_method_params_special_group_specials_inner_rates_inner_instance = UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner.from_json(json)
# print the JSON string representation of the object
print(UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner.to_json())

# convert the object into a dict
update_special_group_method_params_special_group_specials_inner_rates_inner_dict = update_special_group_method_params_special_group_specials_inner_rates_inner_instance.to_dict()
# create an instance of UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner from a dict
update_special_group_method_params_special_group_specials_inner_rates_inner_from_dict = UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner.from_dict(update_special_group_method_params_special_group_specials_inner_rates_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



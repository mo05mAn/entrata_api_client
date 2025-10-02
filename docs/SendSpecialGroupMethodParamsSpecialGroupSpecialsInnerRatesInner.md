# SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_code_id** | **str** | This is an optional field. AR code identifier. | [optional] 
**ar_trigger_id** | **str** | This is an optional field. AR trigger identifier. | [optional] 
**ar_code_type_id** | **str** | This is an optional field. AR code type identifier. | [optional] 
**customer_relationship_id** | **str** | This is an optional field. Customer relationship identifier. | [optional] 
**lease_term_id** | **str** | This is a required field. Lease term identifier. | 
**lease_term_month** | **str** | This is a required field. Integer representation of lease term. | 
**lease_start_window_id** | **str** | This is a required field. Lease start window identifier. | 
**window_start_date** | **str** | This is an optional field. Start date for lease window. | [optional] 
**window_end_date** | **str** | This is an optional field. End date for lease window. | [optional] 
**ar_formula_id** | **str** | This is a required field. AR formula identifier. | 
**rate_interval_start** | **str** | This is an optional field. Month when special starts. | [optional] 
**rate_amount** | **str** | This is a required field. Rate amount. | 
**rate_increase_increment** | **str** | This is an optional field. Increment for percent base formula. | [optional] 
**ar_formula_reference_id** | **str** | This is an optional field. Additional formula information. | [optional] 
**space_configuration_id** | **str** | This is an optional field. Space configuration identifier. | [optional] 
**show_in_entrata** | **str** | This is a required field. Display within Entrata. | 
**show_on_website** | **str** | This is a required field. Display on website. | 

## Example

```python
from openapi_client.models.send_special_group_method_params_special_group_specials_inner_rates_inner import SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner from a JSON string
send_special_group_method_params_special_group_specials_inner_rates_inner_instance = SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner.to_json())

# convert the object into a dict
send_special_group_method_params_special_group_specials_inner_rates_inner_dict = send_special_group_method_params_special_group_specials_inner_rates_inner_instance.to_dict()
# create an instance of SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner from a dict
send_special_group_method_params_special_group_specials_inner_rates_inner_from_dict = SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner.from_dict(send_special_group_method_params_special_group_specials_inner_rates_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



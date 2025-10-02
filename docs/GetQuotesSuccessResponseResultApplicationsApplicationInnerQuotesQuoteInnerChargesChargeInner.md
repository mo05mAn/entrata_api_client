# GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pricing_level_id** | **int** | The pricing level ID. | [optional] 
**pricing_level** | **str** | The pricing level. | [optional] 
**pricing_level_reference_id** | **int** | The reference ID for the pricing level. | [optional] 
**charge_usage_id** | **int** | The charge usage ID. | [optional] 
**charge_usage** | **str** | The usage of the charge. | [optional] 
**charge_timing_id** | **int** | The timing ID for the charge. | [optional] 
**charge_timing** | **str** | The timing for the charge. | [optional] 
**charge_code_type_id** | **int** | The charge code type ID. | [optional] 
**charge_code_type** | **str** | The charge code type. | [optional] 
**charge_code_id** | **int** | The charge code ID. | [optional] 
**charge_code** | **str** | The charge code. | [optional] 
**charge_amount** | **str** | The charge amount. | [optional] 
**tax_amount** | **str** | The tax amount associated with the charge. | [optional] 

## Example

```python
from openapi_client.models.get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_charge_inner import GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner from a JSON string
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_charge_inner_instance = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_charge_inner_dict = get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_charge_inner_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner from a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_charge_inner_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner.from_dict(get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_charge_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



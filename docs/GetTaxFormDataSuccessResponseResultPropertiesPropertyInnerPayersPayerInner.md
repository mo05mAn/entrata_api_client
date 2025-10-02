# GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayersPayerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**payer_type** | **str** | The type of payer (e.g., Business, Individual). | 
**payer_tin_type** | **str** | Type of the payer&#39;s tax identification number. | 
**payer_tin** | **str** | Tax Identification Number of the payer. | 
**payer_business_name_or_name** | **str** | Business name or individual&#39;s name for the payer. | 
**payer_address1** | **str** | Street address of the payer. | [optional] 
**payer_city** | **str** | City where the payer is located. | [optional] 
**payer_state** | **str** | State where the payer is located. | [optional] 
**payer_zip_code** | **str** | Postal code of the payer&#39;s location. | [optional] 

## Example

```python
from openapi_client.models.get_tax_form_data_success_response_result_properties_property_inner_payers_payer_inner import GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayersPayerInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayersPayerInner from a JSON string
get_tax_form_data_success_response_result_properties_property_inner_payers_payer_inner_instance = GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayersPayerInner.from_json(json)
# print the JSON string representation of the object
print(GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayersPayerInner.to_json())

# convert the object into a dict
get_tax_form_data_success_response_result_properties_property_inner_payers_payer_inner_dict = get_tax_form_data_success_response_result_properties_property_inner_payers_payer_inner_instance.to_dict()
# create an instance of GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayersPayerInner from a dict
get_tax_form_data_success_response_result_properties_property_inner_payers_payer_inner_from_dict = GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayersPayerInner.from_dict(get_tax_form_data_success_response_result_properties_property_inner_payers_payer_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



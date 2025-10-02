# GetTaxFormDataSuccessResponseResultPropertiesPropertyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendors** | [**GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendors**](GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendors.md) |  | 
**payers** | [**GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayers**](GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerPayers.md) |  | 
**attributes** | [**GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerAttributes**](GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerAttributes.md) |  | 
**id** | **str** | Unique identifier for the property. | [optional] 

## Example

```python
from entrata_api_client.models.get_tax_form_data_success_response_result_properties_property_inner import GetTaxFormDataSuccessResponseResultPropertiesPropertyInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetTaxFormDataSuccessResponseResultPropertiesPropertyInner from a JSON string
get_tax_form_data_success_response_result_properties_property_inner_instance = GetTaxFormDataSuccessResponseResultPropertiesPropertyInner.from_json(json)
# print the JSON string representation of the object
print(GetTaxFormDataSuccessResponseResultPropertiesPropertyInner.to_json())

# convert the object into a dict
get_tax_form_data_success_response_result_properties_property_inner_dict = get_tax_form_data_success_response_result_properties_property_inner_instance.to_dict()
# create an instance of GetTaxFormDataSuccessResponseResultPropertiesPropertyInner from a dict
get_tax_form_data_success_response_result_properties_property_inner_from_dict = GetTaxFormDataSuccessResponseResultPropertiesPropertyInner.from_dict(get_tax_form_data_success_response_result_properties_property_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



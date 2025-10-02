# GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_id** | **str** | Unique identifier for the vendor. | 
**vendor_type** | **str** | Type of the vendor (e.g., Business, Individual). | 
**vendor_tin_type** | **str** | Type of the vendor&#39;s tax identification number. | 
**vendor_tin** | **str** | Tax Identification Number of the vendor. | 
**vendor_business_nameor_name** | **str** | Business name or individual&#39;s name for the vendor. | 
**name_on_tax_return** | **str** | Legal name of the entity as per tax return. | [optional] 
**vendor_address1** | **str** | Street address of the vendor. | 
**vendor_address2** | **str** | Optional second line of the vendor&#39;s street address. | [optional] 
**vendor_city** | **str** | City where the vendor is located. | 
**vendor_state** | **str** | State where the vendor is located. | 
**vendor_zip_code** | **str** | Postal code of the vendor&#39;s location. | 
**form_type** | **str** | Type of form the vendor receives (e.g., 1099 - MISC). | 
**form1099_boxes** | [**GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInnerForm1099Boxes**](GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInnerForm1099Boxes.md) |  | 

## Example

```python
from entrata_api_client.models.get_tax_form_data_success_response_result_properties_property_inner_vendors_vendor_inner import GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInner from a JSON string
get_tax_form_data_success_response_result_properties_property_inner_vendors_vendor_inner_instance = GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInner.from_json(json)
# print the JSON string representation of the object
print(GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInner.to_json())

# convert the object into a dict
get_tax_form_data_success_response_result_properties_property_inner_vendors_vendor_inner_dict = get_tax_form_data_success_response_result_properties_property_inner_vendors_vendor_inner_instance.to_dict()
# create an instance of GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInner from a dict
get_tax_form_data_success_response_result_properties_property_inner_vendors_vendor_inner_from_dict = GetTaxFormDataSuccessResponseResultPropertiesPropertyInnerVendorsVendorInner.from_dict(get_tax_form_data_success_response_result_properties_property_inner_vendors_vendor_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



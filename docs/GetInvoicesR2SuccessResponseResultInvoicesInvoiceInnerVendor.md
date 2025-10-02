# GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Vendor identifier | 
**name** | **str** | Vendor name | 
**location_name** | **str** | Location name of the vendor | 
**location_code** | **str** | Location code of the vendor | [optional] 
**external_id** | **str** | External ID of the vendor | [optional] 
**address** | [**GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress**](GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress.md) |  | 

## Example

```python
from openapi_client.models.get_invoices_r2_success_response_result_invoices_invoice_inner_vendor import GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor from a JSON string
get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_instance = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor.to_json())

# convert the object into a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_dict = get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_instance.to_dict()
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor from a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_from_dict = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor.from_dict(get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



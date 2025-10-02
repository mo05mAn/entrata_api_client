# GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Vendor ID | 
**name** | **str** | Vendor name | 
**location_name** | **str** | Location name of the vendor | 
**address** | [**GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress**](GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress.md) |  | 

## Example

```python
from openapi_client.models.get_invoices_r1_success_response_result_invoices_invoice_vendor import GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor from a JSON string
get_invoices_r1_success_response_result_invoices_invoice_vendor_instance = GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor.to_json())

# convert the object into a dict
get_invoices_r1_success_response_result_invoices_invoice_vendor_dict = get_invoices_r1_success_response_result_invoices_invoice_vendor_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor from a dict
get_invoices_r1_success_response_result_invoices_invoice_vendor_from_dict = GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor.from_dict(get_invoices_r1_success_response_result_invoices_invoice_vendor_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



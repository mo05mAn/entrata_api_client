# GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**street_line1** | **str** | Street address line 1 | 
**street_line2** | **str** | Street address line 2 | 
**city** | **str** | City | 
**state_code** | **str** | State code | 
**postal_code** | **str** | Postal code | 

## Example

```python
from entrata_api_client.models.get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_address import GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress from a JSON string
get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_address_instance = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress.to_json())

# convert the object into a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_address_dict = get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_address_instance.to_dict()
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress from a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_address_from_dict = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendorAddress.from_dict(get_invoices_r2_success_response_result_invoices_invoice_inner_vendor_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



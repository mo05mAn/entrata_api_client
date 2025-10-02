# GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress


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
from entrata_api_client.models.get_invoices_r1_success_response_result_invoices_invoice_vendor_address import GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress from a JSON string
get_invoices_r1_success_response_result_invoices_invoice_vendor_address_instance = GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress.to_json())

# convert the object into a dict
get_invoices_r1_success_response_result_invoices_invoice_vendor_address_dict = get_invoices_r1_success_response_result_invoices_invoice_vendor_address_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress from a dict
get_invoices_r1_success_response_result_invoices_invoice_vendor_address_from_dict = GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendorAddress.from_dict(get_invoices_r1_success_response_result_invoices_invoice_vendor_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Remittance identifier | 
**name** | **str** | Name of the remittance | 
**ap_payment_type_id** | **str** | Payment type ID | 
**ap_payment_type** | **str** | Payment type | 
**street_line1** | **str** | Street address line 1 | 
**street_line2** | **str** | Street address line 2 | 
**city** | **str** | City | 
**state_code** | **str** | State code | 
**postal_code** | **str** | Postal code | 

## Example

```python
from entrata_api_client.models.get_invoices_r2_success_response_result_invoices_invoice_inner_remittance import GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance from a JSON string
get_invoices_r2_success_response_result_invoices_invoice_inner_remittance_instance = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance.to_json())

# convert the object into a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_remittance_dict = get_invoices_r2_success_response_result_invoices_invoice_inner_remittance_instance.to_dict()
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance from a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_remittance_from_dict = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance.from_dict(get_invoices_r2_success_response_result_invoices_invoice_inner_remittance_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



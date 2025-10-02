# GetInvoicesR1SuccessResponseResultInvoicesInvoice


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the invoice | 
**is_on_hold** | **str** | Flag indicating if the invoice is on hold | 
**invoice_number** | **str** | Invoice number | 
**var_date** | **str** | Invoice date | 
**post_month** | **str** | The month the invoice was posted | 
**due_date** | **str** | Due date of the invoice | 
**remittance** | [**GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance**](GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance.md) |  | 
**vendor** | [**GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor**](GetInvoicesR1SuccessResponseResultInvoicesInvoiceVendor.md) |  | 
**invoice_payments** | [**GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePayments**](GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePayments.md) |  | 
**amount** | **str** | Total invoice amount | 
**amount_due** | **str** | Amount due on the invoice | 
**note** | **str** | Additional note regarding the invoice | 
**is_posted** | **str** | Flag indicating if the invoice is posted | 
**line_items** | [**GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems**](GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems.md) |  | 

## Example

```python
from entrata_api_client.models.get_invoices_r1_success_response_result_invoices_invoice import GetInvoicesR1SuccessResponseResultInvoicesInvoice

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoice from a JSON string
get_invoices_r1_success_response_result_invoices_invoice_instance = GetInvoicesR1SuccessResponseResultInvoicesInvoice.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponseResultInvoicesInvoice.to_json())

# convert the object into a dict
get_invoices_r1_success_response_result_invoices_invoice_dict = get_invoices_r1_success_response_result_invoices_invoice_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoice from a dict
get_invoices_r1_success_response_result_invoices_invoice_from_dict = GetInvoicesR1SuccessResponseResultInvoicesInvoice.from_dict(get_invoices_r1_success_response_result_invoices_invoice_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



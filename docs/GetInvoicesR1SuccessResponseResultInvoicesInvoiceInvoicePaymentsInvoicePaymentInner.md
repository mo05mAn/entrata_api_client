# GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePaymentsInvoicePaymentInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**payment_id** | **str** | Unique identifier for the payment | 
**payment_bank_id** | **str** | Payment bank ID | 
**payment_bank_name** | **str** | Name of the payment bank | 
**payment_bank_account_name** | **str** | Account name of the payment bank | 
**payment_type** | **str** | Type of payment | 
**payment_status** | **str** | Status of the payment | 
**reconciliation_status** | **str** | Reconciliation status of the payment | 
**payment_date** | **str** | Payment date | 
**payment_issued_on** | **str** | Date when the payment was issued | 
**payee_name** | **str** | Name of the payee | 
**payment_number** | **str** | Payment number | 
**payment_amount** | **str** | Amount of the payment | 
**post_month** | **str** | Post month for the payment | 
**post_date** | **str** | Post date for the payment | 
**is_reversed** | **str** | Indicates if the payment is reversed | 
**is_quick_check** | **str** | Indicates if the payment is a quick check | 

## Example

```python
from openapi_client.models.get_invoices_r1_success_response_result_invoices_invoice_invoice_payments_invoice_payment_inner import GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePaymentsInvoicePaymentInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePaymentsInvoicePaymentInner from a JSON string
get_invoices_r1_success_response_result_invoices_invoice_invoice_payments_invoice_payment_inner_instance = GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePaymentsInvoicePaymentInner.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePaymentsInvoicePaymentInner.to_json())

# convert the object into a dict
get_invoices_r1_success_response_result_invoices_invoice_invoice_payments_invoice_payment_inner_dict = get_invoices_r1_success_response_result_invoices_invoice_invoice_payments_invoice_payment_inner_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePaymentsInvoicePaymentInner from a dict
get_invoices_r1_success_response_result_invoices_invoice_invoice_payments_invoice_payment_inner_from_dict = GetInvoicesR1SuccessResponseResultInvoicesInvoiceInvoicePaymentsInvoicePaymentInner.from_dict(get_invoices_r1_success_response_result_invoices_invoice_invoice_payments_invoice_payment_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



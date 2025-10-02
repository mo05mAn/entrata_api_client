# GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePaymentsInvoicePaymentInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**payment_id** | **str** | Payment identifier | 
**payment_bank_id** | **str** | Payment bank identifier | 
**payment_bank_name** | **str** | Payment bank name | 
**payment_bank_account_name** | **str** | Bank account name for the payment | 
**payment_type** | **str** | Type of payment | 
**payment_status** | **str** | Status of the payment | 
**reconciliation_status** | **str** | Reconciliation status of the payment | [optional] 
**payment_date** | **str** | Date of payment | 
**payment_issued_on** | **str** | Issued date of payment | 
**payee_name** | **str** | Payee name | 
**payment_number** | **str** | Payment number | 
**payment_amount** | **str** | Amount paid | 
**post_month** | **str** | Month the payment was posted | 
**post_date** | **str** | Date the payment was posted | 
**is_reversed** | **str** | Flag indicating if payment is reversed | 
**is_quick_check** | **str** | Flag indicating if the payment is a quick check | 

## Example

```python
from entrata_api_client.models.get_invoices_r2_success_response_result_invoices_invoice_inner_invoice_payments_invoice_payment_inner import GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePaymentsInvoicePaymentInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePaymentsInvoicePaymentInner from a JSON string
get_invoices_r2_success_response_result_invoices_invoice_inner_invoice_payments_invoice_payment_inner_instance = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePaymentsInvoicePaymentInner.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePaymentsInvoicePaymentInner.to_json())

# convert the object into a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_invoice_payments_invoice_payment_inner_dict = get_invoices_r2_success_response_result_invoices_invoice_inner_invoice_payments_invoice_payment_inner_instance.to_dict()
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePaymentsInvoicePaymentInner from a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_invoice_payments_invoice_payment_inner_from_dict = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePaymentsInvoicePaymentInner.from_dict(get_invoices_r2_success_response_result_invoices_invoice_inner_invoice_payments_invoice_payment_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



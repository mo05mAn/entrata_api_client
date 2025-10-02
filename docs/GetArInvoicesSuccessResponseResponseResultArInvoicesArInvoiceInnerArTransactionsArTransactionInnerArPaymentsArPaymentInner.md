# GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPaymentsArPaymentInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_payment_id** | **int** | The unique identifier for the payment related to this transaction. | 
**payment_amount** | **int** | The total amount paid for the transaction. | [optional] 
**payment_date** | **str** | The date the payment was made. | [optional] 
**payment_type_id** | **int** | The identifier for the type of payment made. | [optional] 
**payment_type_name** | **str** | The name of the payment method used. | [optional] 
**payment_status_type_id** | **int** | The identifier for the status of the payment. | [optional] 
**payment_status_type_name** | **str** | The name of the payment status. | [optional] 

## Example

```python
from entrata_api_client.models.get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_ar_payments_ar_payment_inner import GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPaymentsArPaymentInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPaymentsArPaymentInner from a JSON string
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_ar_payments_ar_payment_inner_instance = GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPaymentsArPaymentInner.from_json(json)
# print the JSON string representation of the object
print(GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPaymentsArPaymentInner.to_json())

# convert the object into a dict
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_ar_payments_ar_payment_inner_dict = get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_ar_payments_ar_payment_inner_instance.to_dict()
# create an instance of GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPaymentsArPaymentInner from a dict
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_ar_payments_ar_payment_inner_from_dict = GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPaymentsArPaymentInner.from_dict(get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_ar_payments_ar_payment_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique identifier for the AR transaction. | 
**ar_code_id** | **int** | The identifier for the AR code associated with the transaction. | [optional] 
**ar_code_name** | **str** | The name of the AR code associated with the transaction. | [optional] 
**base_amount** | **int** | The base amount for the transaction before taxes. | [optional] 
**tax_rate** | **int** | The tax rate applied to the transaction. | [optional] 
**tax_amount** | **int** | The tax amount for the transaction. | [optional] 
**due_date** | **str** | The date by which the transaction is due. | [optional] 
**from_date** | **str** | The start date of the transaction period. | [optional] 
**to_date** | **str** | The end date of the transaction period. | [optional] 
**ar_payments** | [**GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPayments**](GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInnerArPayments.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner import GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInner from a JSON string
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_instance = GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInner.from_json(json)
# print the JSON string representation of the object
print(GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInner.to_json())

# convert the object into a dict
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_dict = get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_instance.to_dict()
# create an instance of GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInner from a dict
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_from_dict = GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactionsArTransactionInner.from_dict(get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_ar_transactions_ar_transaction_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



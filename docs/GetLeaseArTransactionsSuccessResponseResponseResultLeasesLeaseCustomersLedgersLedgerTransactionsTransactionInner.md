# GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactionsTransactionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique identifier for the transaction. | 
**transaction_type_id** | **int** | The identifier for the type of transaction. | [optional] 
**ar_code_id** | **int** | The identifier for the AR code associated with the transaction. | [optional] 
**ar_code_name** | **str** | The name of the AR code associated with the transaction. | [optional] 
**lease_interval_id** | **int** | The identifier for the lease interval associated with the transaction. | [optional] 
**description** | **str** | Additional details about the transaction. | [optional] 
**transaction_date** | **str** | The date the transaction took place. | [optional] 
**post_date** | **str** | The date the transaction was posted. | [optional] 
**post_month** | **str** | The month the transaction was posted. | [optional] 
**is_temporary** | **bool** | Indicates whether the transaction is temporary. | [optional] 
**balance_due** | **int** | The remaining balance due on the transaction. | [optional] 
**amount** | **int** | The amount involved in the transaction. | [optional] 
**amount_paid** | **int** | The amount already paid toward the transaction. | [optional] 
**scheduled_charge_id** | **int** | The identifier for the scheduled charge associated with the transaction. | [optional] 
**credit_ar_transaction_ids** | **str** | A list of credit AR transaction IDs associated with the transaction. | [optional] 
**ar_payment_id** | **int** | The identifier for the payment related to the transaction. | [optional] 

## Example

```python
from openapi_client.models.get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_transactions_transaction_inner import GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactionsTransactionInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactionsTransactionInner from a JSON string
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_transactions_transaction_inner_instance = GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactionsTransactionInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactionsTransactionInner.to_json())

# convert the object into a dict
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_transactions_transaction_inner_dict = get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_transactions_transaction_inner_instance.to_dict()
# create an instance of GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactionsTransactionInner from a dict
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_transactions_transaction_inner_from_dict = GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactionsTransactionInner.from_dict(get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_transactions_transaction_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



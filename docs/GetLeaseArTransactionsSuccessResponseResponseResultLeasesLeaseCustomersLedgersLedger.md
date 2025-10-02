# GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedger


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique identifier for the ledger. | 
**name** | **str** | The name of the ledger associated with the lease. | [optional] 
**balance** | **int** | The current balance of the ledger. | [optional] 
**past_due_balance** | **int** | The overdue balance of the ledger. | [optional] 
**write_off** | **int** | The amount that has been written off from the ledger. | [optional] 
**transactions** | [**GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactions**](GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedgerTransactions.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger import GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedger

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedger from a JSON string
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_instance = GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedger.from_json(json)
# print the JSON string representation of the object
print(GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedger.to_json())

# convert the object into a dict
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_dict = get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_instance.to_dict()
# create an instance of GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedger from a dict
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_from_dict = GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersLedgersLedger.from_dict(get_lease_ar_transactions_success_response_response_result_leases_lease_customers_ledgers_ledger_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



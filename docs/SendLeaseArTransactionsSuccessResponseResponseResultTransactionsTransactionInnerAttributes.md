# SendLeaseArTransactionsSuccessResponseResponseResultTransactionsTransactionInnerAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reference_id** | **int** | The reference identifier for the transaction | 
**transaction_id** | **str** | The transaction identifier | 
**status** | **str** | The status of the transaction | 
**message** | **str** | Message associated with the transaction | 

## Example

```python
from entrata_api_client.models.send_lease_ar_transactions_success_response_response_result_transactions_transaction_inner_attributes import SendLeaseArTransactionsSuccessResponseResponseResultTransactionsTransactionInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactionsSuccessResponseResponseResultTransactionsTransactionInnerAttributes from a JSON string
send_lease_ar_transactions_success_response_response_result_transactions_transaction_inner_attributes_instance = SendLeaseArTransactionsSuccessResponseResponseResultTransactionsTransactionInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactionsSuccessResponseResponseResultTransactionsTransactionInnerAttributes.to_json())

# convert the object into a dict
send_lease_ar_transactions_success_response_response_result_transactions_transaction_inner_attributes_dict = send_lease_ar_transactions_success_response_response_result_transactions_transaction_inner_attributes_instance.to_dict()
# create an instance of SendLeaseArTransactionsSuccessResponseResponseResultTransactionsTransactionInnerAttributes from a dict
send_lease_ar_transactions_success_response_response_result_transactions_transaction_inner_attributes_from_dict = SendLeaseArTransactionsSuccessResponseResponseResultTransactionsTransactionInnerAttributes.from_dict(send_lease_ar_transactions_success_response_response_result_transactions_transaction_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



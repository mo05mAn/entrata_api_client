# GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlTotal


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**opening_balance** | **str** | The opening balance of the transaction. | 
**debit_opening_balance** | **str** | The debit opening balance. | 
**credit_opening_balance** | **str** | The credit opening balance. | 
**debit_closing_balance** | **str** | The debit closing balance. | 
**credit_closing_balance** | **str** | The credit closing balance. | 
**net_change** | **str** | The net change in the transaction. | 
**closing_balance** | **str** | The closing balance of the transaction. | 

## Example

```python
from entrata_api_client.models.get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_total import GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlTotal

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlTotal from a JSON string
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_total_instance = GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlTotal.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlTotal.to_json())

# convert the object into a dict
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_total_dict = get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_total_instance.to_dict()
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlTotal from a dict
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_total_from_dict = GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlTotal.from_dict(get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_total_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



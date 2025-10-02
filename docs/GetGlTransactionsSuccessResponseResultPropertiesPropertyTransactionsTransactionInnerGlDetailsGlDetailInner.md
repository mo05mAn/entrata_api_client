# GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transaction_date** | **str** | The date of the transaction. | 
**post_month** | **str** | The posting month of the transaction. | 
**post_date** | **str** | The posting date of the transaction. | 
**debit** | **str** | The debit amount of the transaction. | 
**credit** | **str** | The credit amount of the transaction. | 
**balance** | **str** | The balance after the transaction. | 
**reference** | **str** | The reference for the transaction. | 
**memo** | **str** | The memo for the transaction. | 
**attributes** | [**GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInnerAttributes**](GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInnerAttributes.md) |  | 

## Example

```python
from entrata_api_client.models.get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_gl_detail_inner import GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner from a JSON string
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_gl_detail_inner_instance = GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner.to_json())

# convert the object into a dict
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_gl_detail_inner_dict = get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_gl_detail_inner_instance.to_dict()
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner from a dict
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_gl_detail_inner_from_dict = GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner.from_dict(get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_gl_detail_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gl_detail** | [**List[GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner]**](GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetailsGlDetailInner.md) | A list of GL detail entries for the transaction. | 

## Example

```python
from entrata_api_client.models.get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details import GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetails

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetails from a JSON string
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_instance = GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetails.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetails.to_json())

# convert the object into a dict
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_dict = get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_instance.to_dict()
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetails from a dict
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_from_dict = GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerGlDetails.from_dict(get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_gl_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



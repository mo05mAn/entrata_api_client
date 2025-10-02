# GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **str** | The unique identifier for the account. | 
**account_name** | **str** | The name of the account. | 
**account_number** | **str** | The account number. | 
**external_id** | **str** | The external ID associated with the account. | [optional] 

## Example

```python
from entrata_api_client.models.get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_attributes import GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerAttributes from a JSON string
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_attributes_instance = GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerAttributes.to_json())

# convert the object into a dict
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_attributes_dict = get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_attributes_instance.to_dict()
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerAttributes from a dict
get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_attributes_from_dict = GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactionsTransactionInnerAttributes.from_dict(get_gl_transactions_success_response_result_properties_property_transactions_transaction_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



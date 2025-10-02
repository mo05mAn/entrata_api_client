# GetGlTransactionsSuccessResponseResultPropertiesProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_cash_book** | **str** | Indicates whether the property is a cash book. | 
**transactions** | [**GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactions**](GetGlTransactionsSuccessResponseResultPropertiesPropertyTransactions.md) |  | 
**attributes** | [**GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes**](GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes.md) |  | 

## Example

```python
from entrata_api_client.models.get_gl_transactions_success_response_result_properties_property import GetGlTransactionsSuccessResponseResultPropertiesProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesProperty from a JSON string
get_gl_transactions_success_response_result_properties_property_instance = GetGlTransactionsSuccessResponseResultPropertiesProperty.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsSuccessResponseResultPropertiesProperty.to_json())

# convert the object into a dict
get_gl_transactions_success_response_result_properties_property_dict = get_gl_transactions_success_response_result_properties_property_instance.to_dict()
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesProperty from a dict
get_gl_transactions_success_response_result_properties_property_from_dict = GetGlTransactionsSuccessResponseResultPropertiesProperty.from_dict(get_gl_transactions_success_response_result_properties_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



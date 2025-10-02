# GetGlTransactionsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. | 
**gl_account_from** | **int** | This is an optional field. This field accepts single value. | [optional] 
**gl_account_to** | **int** | This is an optional field. This field accepts single value. | [optional] 
**post_month_from** | **date** | This is an optional field. This field accepts single value. If no post month is provided, then the default post month of the prope rty will be used. If multiple properties are passed then the post mon th of any property would be used randomly. | [optional] 
**post_month_to** | **date** | This is an optional field. This field accepts single value. | [optional] 
**post_date_from** | **date** | This is an optional field. This field accepts single value. | [optional] 
**post_date_to** | **date** | This is an optional field. This field accepts single value. | [optional] 
**is_cash_book** | **int** | This is an optional field. This field accepts single value. | [optional] 
**is_detailed** | **int** | This is an optional field. This field accepts single value. | [optional] 
**gl_tree_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**gl_book_type_ids** | **int** |   This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**transaction_date_from** | **date** | This is an optional field. This field accepts single value. This is the actual system created date of the transaction. | [optional] 
**transaction_date_to** | **date** | This is an optional field. This field accepts single value. This is the actual system created date of the transaction. | [optional] 
**exclude_ap_transactions** | **int** | This is an optional field. This field accepts single value. This flag will filter off any ap transactions from the response. | [optional] 
**exclude_ar_transactions** | **int** | This is an optional field. This field accepts single value. This flag will filter off any Ar Transactions from the response. | [optional] 
**exclude_exported_transactions** | **int** | This is an optional field. This field accepts single value. If passed as true (1) the API will not return any transaction that was previously marked exported using the markGlTransactionsExported API. Transaction exported under a different export format in Entrata wil l still qualify to be returned until specifically marked exported over the markGlTransactionsExported API. | [optional] 

## Example

```python
from openapi_client.models.get_gl_transactions_method_params import GetGlTransactionsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsMethodParams from a JSON string
get_gl_transactions_method_params_instance = GetGlTransactionsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsMethodParams.to_json())

# convert the object into a dict
get_gl_transactions_method_params_dict = get_gl_transactions_method_params_instance.to_dict()
# create an instance of GetGlTransactionsMethodParams from a dict
get_gl_transactions_method_params_from_dict = GetGlTransactionsMethodParams.from_dict(get_gl_transactions_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



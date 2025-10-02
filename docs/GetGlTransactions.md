# GetGlTransactions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetGlTransactionsMethod**](GetGlTransactionsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_gl_transactions import GetGlTransactions

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactions from a JSON string
get_gl_transactions_instance = GetGlTransactions.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactions.to_json())

# convert the object into a dict
get_gl_transactions_dict = get_gl_transactions_instance.to_dict()
# create an instance of GetGlTransactions from a dict
get_gl_transactions_from_dict = GetGlTransactions.from_dict(get_gl_transactions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



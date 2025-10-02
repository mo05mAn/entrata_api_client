# GetGlTransactionsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetGlTransactionsMethodParams**](GetGlTransactionsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_gl_transactions_method import GetGlTransactionsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsMethod from a JSON string
get_gl_transactions_method_instance = GetGlTransactionsMethod.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsMethod.to_json())

# convert the object into a dict
get_gl_transactions_method_dict = get_gl_transactions_method_instance.to_dict()
# create an instance of GetGlTransactionsMethod from a dict
get_gl_transactions_method_from_dict = GetGlTransactionsMethod.from_dict(get_gl_transactions_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



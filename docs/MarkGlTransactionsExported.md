# MarkGlTransactionsExported


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**MarkGlTransactionsExportedMethod**](MarkGlTransactionsExportedMethod.md) |  | 

## Example

```python
from openapi_client.models.mark_gl_transactions_exported import MarkGlTransactionsExported

# TODO update the JSON string below
json = "{}"
# create an instance of MarkGlTransactionsExported from a JSON string
mark_gl_transactions_exported_instance = MarkGlTransactionsExported.from_json(json)
# print the JSON string representation of the object
print(MarkGlTransactionsExported.to_json())

# convert the object into a dict
mark_gl_transactions_exported_dict = mark_gl_transactions_exported_instance.to_dict()
# create an instance of MarkGlTransactionsExported from a dict
mark_gl_transactions_exported_from_dict = MarkGlTransactionsExported.from_dict(mark_gl_transactions_exported_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



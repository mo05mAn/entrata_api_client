# MarkGlTransactionsExportedMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gl_detail_id** | **int** | This is a required field. This field accepts comma seperated multiple values. | 

## Example

```python
from openapi_client.models.mark_gl_transactions_exported_method_params import MarkGlTransactionsExportedMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of MarkGlTransactionsExportedMethodParams from a JSON string
mark_gl_transactions_exported_method_params_instance = MarkGlTransactionsExportedMethodParams.from_json(json)
# print the JSON string representation of the object
print(MarkGlTransactionsExportedMethodParams.to_json())

# convert the object into a dict
mark_gl_transactions_exported_method_params_dict = mark_gl_transactions_exported_method_params_instance.to_dict()
# create an instance of MarkGlTransactionsExportedMethodParams from a dict
mark_gl_transactions_exported_method_params_from_dict = MarkGlTransactionsExportedMethodParams.from_dict(mark_gl_transactions_exported_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



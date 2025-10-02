# MarkGlTransactionsExportedSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | The status of the operation. | 
**message** | **str** | Detailed message about the operation. | 

## Example

```python
from entrata_api_client.models.mark_gl_transactions_exported_success_response_result import MarkGlTransactionsExportedSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of MarkGlTransactionsExportedSuccessResponseResult from a JSON string
mark_gl_transactions_exported_success_response_result_instance = MarkGlTransactionsExportedSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(MarkGlTransactionsExportedSuccessResponseResult.to_json())

# convert the object into a dict
mark_gl_transactions_exported_success_response_result_dict = mark_gl_transactions_exported_success_response_result_instance.to_dict()
# create an instance of MarkGlTransactionsExportedSuccessResponseResult from a dict
mark_gl_transactions_exported_success_response_result_from_dict = MarkGlTransactionsExportedSuccessResponseResult.from_dict(mark_gl_transactions_exported_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



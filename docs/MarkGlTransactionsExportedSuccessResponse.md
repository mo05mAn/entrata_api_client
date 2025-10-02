# MarkGlTransactionsExportedSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**MarkGlTransactionsExportedSuccessResponseResult**](MarkGlTransactionsExportedSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.mark_gl_transactions_exported_success_response import MarkGlTransactionsExportedSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MarkGlTransactionsExportedSuccessResponse from a JSON string
mark_gl_transactions_exported_success_response_instance = MarkGlTransactionsExportedSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(MarkGlTransactionsExportedSuccessResponse.to_json())

# convert the object into a dict
mark_gl_transactions_exported_success_response_dict = mark_gl_transactions_exported_success_response_instance.to_dict()
# create an instance of MarkGlTransactionsExportedSuccessResponse from a dict
mark_gl_transactions_exported_success_response_from_dict = MarkGlTransactionsExportedSuccessResponse.from_dict(mark_gl_transactions_exported_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



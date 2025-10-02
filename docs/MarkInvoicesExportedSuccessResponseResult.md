# MarkInvoicesExportedSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **str** | Message indicating the success of the export action. | [optional] 

## Example

```python
from openapi_client.models.mark_invoices_exported_success_response_result import MarkInvoicesExportedSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of MarkInvoicesExportedSuccessResponseResult from a JSON string
mark_invoices_exported_success_response_result_instance = MarkInvoicesExportedSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(MarkInvoicesExportedSuccessResponseResult.to_json())

# convert the object into a dict
mark_invoices_exported_success_response_result_dict = mark_invoices_exported_success_response_result_instance.to_dict()
# create an instance of MarkInvoicesExportedSuccessResponseResult from a dict
mark_invoices_exported_success_response_result_from_dict = MarkInvoicesExportedSuccessResponseResult.from_dict(mark_invoices_exported_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



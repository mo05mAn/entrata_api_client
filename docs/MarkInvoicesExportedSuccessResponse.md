# MarkInvoicesExportedSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request. | 
**result** | [**MarkInvoicesExportedSuccessResponseResult**](MarkInvoicesExportedSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.mark_invoices_exported_success_response import MarkInvoicesExportedSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MarkInvoicesExportedSuccessResponse from a JSON string
mark_invoices_exported_success_response_instance = MarkInvoicesExportedSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(MarkInvoicesExportedSuccessResponse.to_json())

# convert the object into a dict
mark_invoices_exported_success_response_dict = mark_invoices_exported_success_response_instance.to_dict()
# create an instance of MarkInvoicesExportedSuccessResponse from a dict
mark_invoices_exported_success_response_from_dict = MarkInvoicesExportedSuccessResponse.from_dict(mark_invoices_exported_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



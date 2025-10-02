# MarkInvoicesExportedMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**MarkInvoicesExportedMethodParams**](MarkInvoicesExportedMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.mark_invoices_exported_method import MarkInvoicesExportedMethod

# TODO update the JSON string below
json = "{}"
# create an instance of MarkInvoicesExportedMethod from a JSON string
mark_invoices_exported_method_instance = MarkInvoicesExportedMethod.from_json(json)
# print the JSON string representation of the object
print(MarkInvoicesExportedMethod.to_json())

# convert the object into a dict
mark_invoices_exported_method_dict = mark_invoices_exported_method_instance.to_dict()
# create an instance of MarkInvoicesExportedMethod from a dict
mark_invoices_exported_method_from_dict = MarkInvoicesExportedMethod.from_dict(mark_invoices_exported_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



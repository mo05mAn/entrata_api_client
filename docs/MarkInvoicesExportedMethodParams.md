# MarkInvoicesExportedMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**line_item_id** | **int** | This is a required field. This field accepts comma seperated multiple values. | 

## Example

```python
from entrata_api_client.models.mark_invoices_exported_method_params import MarkInvoicesExportedMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of MarkInvoicesExportedMethodParams from a JSON string
mark_invoices_exported_method_params_instance = MarkInvoicesExportedMethodParams.from_json(json)
# print the JSON string representation of the object
print(MarkInvoicesExportedMethodParams.to_json())

# convert the object into a dict
mark_invoices_exported_method_params_dict = mark_invoices_exported_method_params_instance.to_dict()
# create an instance of MarkInvoicesExportedMethodParams from a dict
mark_invoices_exported_method_params_from_dict = MarkInvoicesExportedMethodParams.from_dict(mark_invoices_exported_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



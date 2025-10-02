# MarkInvoicesExported


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**MarkInvoicesExportedMethod**](MarkInvoicesExportedMethod.md) |  | 

## Example

```python
from entrata_api_client.models.mark_invoices_exported import MarkInvoicesExported

# TODO update the JSON string below
json = "{}"
# create an instance of MarkInvoicesExported from a JSON string
mark_invoices_exported_instance = MarkInvoicesExported.from_json(json)
# print the JSON string representation of the object
print(MarkInvoicesExported.to_json())

# convert the object into a dict
mark_invoices_exported_dict = mark_invoices_exported_instance.to_dict()
# create an instance of MarkInvoicesExported from a dict
mark_invoices_exported_from_dict = MarkInvoicesExported.from_dict(mark_invoices_exported_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# UpdateInvoicesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateInvoicesMethodParams**](UpdateInvoicesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_invoices_method import UpdateInvoicesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateInvoicesMethod from a JSON string
update_invoices_method_instance = UpdateInvoicesMethod.from_json(json)
# print the JSON string representation of the object
print(UpdateInvoicesMethod.to_json())

# convert the object into a dict
update_invoices_method_dict = update_invoices_method_instance.to_dict()
# create an instance of UpdateInvoicesMethod from a dict
update_invoices_method_from_dict = UpdateInvoicesMethod.from_dict(update_invoices_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



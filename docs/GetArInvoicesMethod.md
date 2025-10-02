# GetArInvoicesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetArInvoicesMethodParams**](GetArInvoicesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_ar_invoices_method import GetArInvoicesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetArInvoicesMethod from a JSON string
get_ar_invoices_method_instance = GetArInvoicesMethod.from_json(json)
# print the JSON string representation of the object
print(GetArInvoicesMethod.to_json())

# convert the object into a dict
get_ar_invoices_method_dict = get_ar_invoices_method_instance.to_dict()
# create an instance of GetArInvoicesMethod from a dict
get_ar_invoices_method_from_dict = GetArInvoicesMethod.from_dict(get_ar_invoices_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



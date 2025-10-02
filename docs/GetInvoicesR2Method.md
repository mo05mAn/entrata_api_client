# GetInvoicesR2Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetInvoicesR2MethodParams**](GetInvoicesR2MethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_invoices_r2_method import GetInvoicesR2Method

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2Method from a JSON string
get_invoices_r2_method_instance = GetInvoicesR2Method.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2Method.to_json())

# convert the object into a dict
get_invoices_r2_method_dict = get_invoices_r2_method_instance.to_dict()
# create an instance of GetInvoicesR2Method from a dict
get_invoices_r2_method_from_dict = GetInvoicesR2Method.from_dict(get_invoices_r2_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



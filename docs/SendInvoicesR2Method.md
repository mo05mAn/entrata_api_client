# SendInvoicesR2Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendInvoicesR2MethodParams**](SendInvoicesR2MethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_invoices_r2_method import SendInvoicesR2Method

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR2Method from a JSON string
send_invoices_r2_method_instance = SendInvoicesR2Method.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR2Method.to_json())

# convert the object into a dict
send_invoices_r2_method_dict = send_invoices_r2_method_instance.to_dict()
# create an instance of SendInvoicesR2Method from a dict
send_invoices_r2_method_from_dict = SendInvoicesR2Method.from_dict(send_invoices_r2_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



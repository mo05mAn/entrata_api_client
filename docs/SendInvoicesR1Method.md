# SendInvoicesR1Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendInvoicesR1MethodParams**](SendInvoicesR1MethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_invoices_r1_method import SendInvoicesR1Method

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR1Method from a JSON string
send_invoices_r1_method_instance = SendInvoicesR1Method.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR1Method.to_json())

# convert the object into a dict
send_invoices_r1_method_dict = send_invoices_r1_method_instance.to_dict()
# create an instance of SendInvoicesR1Method from a dict
send_invoices_r1_method_from_dict = SendInvoicesR1Method.from_dict(send_invoices_r1_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetInvoicesR1Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetInvoicesR1MethodParams**](GetInvoicesR1MethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_invoices_r1_method import GetInvoicesR1Method

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1Method from a JSON string
get_invoices_r1_method_instance = GetInvoicesR1Method.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1Method.to_json())

# convert the object into a dict
get_invoices_r1_method_dict = get_invoices_r1_method_instance.to_dict()
# create an instance of GetInvoicesR1Method from a dict
get_invoices_r1_method_from_dict = GetInvoicesR1Method.from_dict(get_invoices_r1_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



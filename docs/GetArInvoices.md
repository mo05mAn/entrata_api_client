# GetArInvoices


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetArInvoicesMethod**](GetArInvoicesMethod.md) |  | 

## Example

```python
from openapi_client.models.get_ar_invoices import GetArInvoices

# TODO update the JSON string below
json = "{}"
# create an instance of GetArInvoices from a JSON string
get_ar_invoices_instance = GetArInvoices.from_json(json)
# print the JSON string representation of the object
print(GetArInvoices.to_json())

# convert the object into a dict
get_ar_invoices_dict = get_ar_invoices_instance.to_dict()
# create an instance of GetArInvoices from a dict
get_ar_invoices_from_dict = GetArInvoices.from_dict(get_ar_invoices_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



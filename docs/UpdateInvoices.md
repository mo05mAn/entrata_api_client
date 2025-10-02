# UpdateInvoices


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateInvoicesMethod**](UpdateInvoicesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.update_invoices import UpdateInvoices

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateInvoices from a JSON string
update_invoices_instance = UpdateInvoices.from_json(json)
# print the JSON string representation of the object
print(UpdateInvoices.to_json())

# convert the object into a dict
update_invoices_dict = update_invoices_instance.to_dict()
# create an instance of UpdateInvoices from a dict
update_invoices_from_dict = UpdateInvoices.from_dict(update_invoices_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



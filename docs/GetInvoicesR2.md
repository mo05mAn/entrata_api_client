# GetInvoicesR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetInvoicesR2Method**](GetInvoicesR2Method.md) |  | 

## Example

```python
from entrata_api_client.models.get_invoices_r2 import GetInvoicesR2

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2 from a JSON string
get_invoices_r2_instance = GetInvoicesR2.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2.to_json())

# convert the object into a dict
get_invoices_r2_dict = get_invoices_r2_instance.to_dict()
# create an instance of GetInvoicesR2 from a dict
get_invoices_r2_from_dict = GetInvoicesR2.from_dict(get_invoices_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



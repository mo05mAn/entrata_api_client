# SendInvoicesR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendInvoicesR2Method**](SendInvoicesR2Method.md) |  | 

## Example

```python
from entrata_api_client.models.send_invoices_r2 import SendInvoicesR2

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR2 from a JSON string
send_invoices_r2_instance = SendInvoicesR2.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR2.to_json())

# convert the object into a dict
send_invoices_r2_dict = send_invoices_r2_instance.to_dict()
# create an instance of SendInvoicesR2 from a dict
send_invoices_r2_from_dict = SendInvoicesR2.from_dict(send_invoices_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



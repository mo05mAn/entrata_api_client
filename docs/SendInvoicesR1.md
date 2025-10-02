# SendInvoicesR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendInvoicesR1Method**](SendInvoicesR1Method.md) |  | 

## Example

```python
from openapi_client.models.send_invoices_r1 import SendInvoicesR1

# TODO update the JSON string below
json = "{}"
# create an instance of SendInvoicesR1 from a JSON string
send_invoices_r1_instance = SendInvoicesR1.from_json(json)
# print the JSON string representation of the object
print(SendInvoicesR1.to_json())

# convert the object into a dict
send_invoices_r1_dict = send_invoices_r1_instance.to_dict()
# create an instance of SendInvoicesR1 from a dict
send_invoices_r1_from_dict = SendInvoicesR1.from_dict(send_invoices_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



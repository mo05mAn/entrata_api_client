# SendVendorsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendVendorsMethodParams**](SendVendorsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_vendors_method import SendVendorsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendVendorsMethod from a JSON string
send_vendors_method_instance = SendVendorsMethod.from_json(json)
# print the JSON string representation of the object
print(SendVendorsMethod.to_json())

# convert the object into a dict
send_vendors_method_dict = send_vendors_method_instance.to_dict()
# create an instance of SendVendorsMethod from a dict
send_vendors_method_from_dict = SendVendorsMethod.from_dict(send_vendors_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



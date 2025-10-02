# SendVendors


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendVendorsMethod**](SendVendorsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_vendors import SendVendors

# TODO update the JSON string below
json = "{}"
# create an instance of SendVendors from a JSON string
send_vendors_instance = SendVendors.from_json(json)
# print the JSON string representation of the object
print(SendVendors.to_json())

# convert the object into a dict
send_vendors_dict = send_vendors_instance.to_dict()
# create an instance of SendVendors from a dict
send_vendors_from_dict = SendVendors.from_dict(send_vendors_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



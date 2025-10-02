# GetVendors


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetVendorsMethod**](GetVendorsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_vendors import GetVendors

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendors from a JSON string
get_vendors_instance = GetVendors.from_json(json)
# print the JSON string representation of the object
print(GetVendors.to_json())

# convert the object into a dict
get_vendors_dict = get_vendors_instance.to_dict()
# create an instance of GetVendors from a dict
get_vendors_from_dict = GetVendors.from_dict(get_vendors_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



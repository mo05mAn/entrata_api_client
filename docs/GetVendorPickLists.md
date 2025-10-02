# GetVendorPickLists


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetVendorPickListsMethod**](GetVendorPickListsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_vendor_pick_lists import GetVendorPickLists

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorPickLists from a JSON string
get_vendor_pick_lists_instance = GetVendorPickLists.from_json(json)
# print the JSON string representation of the object
print(GetVendorPickLists.to_json())

# convert the object into a dict
get_vendor_pick_lists_dict = get_vendor_pick_lists_instance.to_dict()
# create an instance of GetVendorPickLists from a dict
get_vendor_pick_lists_from_dict = GetVendorPickLists.from_dict(get_vendor_pick_lists_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



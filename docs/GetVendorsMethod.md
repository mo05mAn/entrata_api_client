# GetVendorsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetVendorsMethodParams**](GetVendorsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_vendors_method import GetVendorsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsMethod from a JSON string
get_vendors_method_instance = GetVendorsMethod.from_json(json)
# print the JSON string representation of the object
print(GetVendorsMethod.to_json())

# convert the object into a dict
get_vendors_method_dict = get_vendors_method_instance.to_dict()
# create an instance of GetVendorsMethod from a dict
get_vendors_method_from_dict = GetVendorsMethod.from_dict(get_vendors_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



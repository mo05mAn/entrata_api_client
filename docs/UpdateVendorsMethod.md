# UpdateVendorsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateVendorsMethodParams**](UpdateVendorsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_vendors_method import UpdateVendorsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateVendorsMethod from a JSON string
update_vendors_method_instance = UpdateVendorsMethod.from_json(json)
# print the JSON string representation of the object
print(UpdateVendorsMethod.to_json())

# convert the object into a dict
update_vendors_method_dict = update_vendors_method_instance.to_dict()
# create an instance of UpdateVendorsMethod from a dict
update_vendors_method_from_dict = UpdateVendorsMethod.from_dict(update_vendors_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



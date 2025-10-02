# UpdateVendors


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateVendorsMethod**](UpdateVendorsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.update_vendors import UpdateVendors

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateVendors from a JSON string
update_vendors_instance = UpdateVendors.from_json(json)
# print the JSON string representation of the object
print(UpdateVendors.to_json())

# convert the object into a dict
update_vendors_dict = update_vendors_instance.to_dict()
# create an instance of UpdateVendors from a dict
update_vendors_from_dict = UpdateVendors.from_dict(update_vendors_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



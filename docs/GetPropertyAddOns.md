# GetPropertyAddOns


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetPropertyAddOnsMethod**](GetPropertyAddOnsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_add_ons import GetPropertyAddOns

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAddOns from a JSON string
get_property_add_ons_instance = GetPropertyAddOns.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAddOns.to_json())

# convert the object into a dict
get_property_add_ons_dict = get_property_add_ons_instance.to_dict()
# create an instance of GetPropertyAddOns from a dict
get_property_add_ons_from_dict = GetPropertyAddOns.from_dict(get_property_add_ons_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



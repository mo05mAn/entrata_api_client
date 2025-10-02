# GetPropertyAddOnsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPropertyAddOnsMethodParams**](GetPropertyAddOnsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_property_add_ons_method import GetPropertyAddOnsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAddOnsMethod from a JSON string
get_property_add_ons_method_instance = GetPropertyAddOnsMethod.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAddOnsMethod.to_json())

# convert the object into a dict
get_property_add_ons_method_dict = get_property_add_ons_method_instance.to_dict()
# create an instance of GetPropertyAddOnsMethod from a dict
get_property_add_ons_method_from_dict = GetPropertyAddOnsMethod.from_dict(get_property_add_ons_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



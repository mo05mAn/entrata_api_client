# GetPropertyUnits


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetPropertyUnitsMethod**](GetPropertyUnitsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_property_units import GetPropertyUnits

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyUnits from a JSON string
get_property_units_instance = GetPropertyUnits.from_json(json)
# print the JSON string representation of the object
print(GetPropertyUnits.to_json())

# convert the object into a dict
get_property_units_dict = get_property_units_instance.to_dict()
# create an instance of GetPropertyUnits from a dict
get_property_units_from_dict = GetPropertyUnits.from_dict(get_property_units_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetUnitTypes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetUnitTypesMethod**](GetUnitTypesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_unit_types import GetUnitTypes

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitTypes from a JSON string
get_unit_types_instance = GetUnitTypes.from_json(json)
# print the JSON string representation of the object
print(GetUnitTypes.to_json())

# convert the object into a dict
get_unit_types_dict = get_unit_types_instance.to_dict()
# create an instance of GetUnitTypes from a dict
get_unit_types_from_dict = GetUnitTypes.from_dict(get_unit_types_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



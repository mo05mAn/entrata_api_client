# GetMitsPropertyUnits


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetMitsPropertyUnitsMethod**](GetMitsPropertyUnitsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_mits_property_units import GetMitsPropertyUnits

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsPropertyUnits from a JSON string
get_mits_property_units_instance = GetMitsPropertyUnits.from_json(json)
# print the JSON string representation of the object
print(GetMitsPropertyUnits.to_json())

# convert the object into a dict
get_mits_property_units_dict = get_mits_property_units_instance.to_dict()
# create an instance of GetMitsPropertyUnits from a dict
get_mits_property_units_from_dict = GetMitsPropertyUnits.from_dict(get_mits_property_units_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



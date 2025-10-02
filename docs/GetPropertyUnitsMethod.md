# GetPropertyUnitsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPropertyUnitsMethodParams**](GetPropertyUnitsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_property_units_method import GetPropertyUnitsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyUnitsMethod from a JSON string
get_property_units_method_instance = GetPropertyUnitsMethod.from_json(json)
# print the JSON string representation of the object
print(GetPropertyUnitsMethod.to_json())

# convert the object into a dict
get_property_units_method_dict = get_property_units_method_instance.to_dict()
# create an instance of GetPropertyUnitsMethod from a dict
get_property_units_method_from_dict = GetPropertyUnitsMethod.from_dict(get_property_units_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



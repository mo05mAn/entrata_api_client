# GetUnitTypesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetUnitTypesMethodParams**](GetUnitTypesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_unit_types_method import GetUnitTypesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitTypesMethod from a JSON string
get_unit_types_method_instance = GetUnitTypesMethod.from_json(json)
# print the JSON string representation of the object
print(GetUnitTypesMethod.to_json())

# convert the object into a dict
get_unit_types_method_dict = get_unit_types_method_instance.to_dict()
# create an instance of GetUnitTypesMethod from a dict
get_unit_types_method_from_dict = GetUnitTypesMethod.from_dict(get_unit_types_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



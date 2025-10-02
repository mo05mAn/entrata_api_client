# GetFloorPlansMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetFloorPlansMethodParams**](GetFloorPlansMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_floor_plans_method import GetFloorPlansMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansMethod from a JSON string
get_floor_plans_method_instance = GetFloorPlansMethod.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansMethod.to_json())

# convert the object into a dict
get_floor_plans_method_dict = get_floor_plans_method_instance.to_dict()
# create an instance of GetFloorPlansMethod from a dict
get_floor_plans_method_from_dict = GetFloorPlansMethod.from_dict(get_floor_plans_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



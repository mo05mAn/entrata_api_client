# GetFloorPlans


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetFloorPlansMethod**](GetFloorPlansMethod.md) |  | 

## Example

```python
from openapi_client.models.get_floor_plans import GetFloorPlans

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlans from a JSON string
get_floor_plans_instance = GetFloorPlans.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlans.to_json())

# convert the object into a dict
get_floor_plans_dict = get_floor_plans_instance.to_dict()
# create an instance of GetFloorPlans from a dict
get_floor_plans_from_dict = GetFloorPlans.from_dict(get_floor_plans_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



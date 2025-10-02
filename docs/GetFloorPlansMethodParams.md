# GetFloorPlansMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**property_floor_plan_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. propertyFloorPlanIds. | [optional] 
**use_property_preferences** | **int** | This is an optional field. This field accepts single value. Checks for the property settings manipulate floorplan data and honour those settings. | [optional] 
**include_disabled_floorplans** | **int** | This is an optional field. This field accepts single value. If provided value is 1, then user should get disabled floorplans along with the enabled one. | [optional] 

## Example

```python
from openapi_client.models.get_floor_plans_method_params import GetFloorPlansMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansMethodParams from a JSON string
get_floor_plans_method_params_instance = GetFloorPlansMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansMethodParams.to_json())

# convert the object into a dict
get_floor_plans_method_params_dict = get_floor_plans_method_params_instance.to_dict()
# create an instance of GetFloorPlansMethodParams from a dict
get_floor_plans_method_params_from_dict = GetFloorPlansMethodParams.from_dict(get_floor_plans_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



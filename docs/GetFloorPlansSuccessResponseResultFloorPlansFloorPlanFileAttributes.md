# GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes

Attributes related to the file

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **str** | ID of the file | [optional] 
**active** | **str** | Whether the file is active | [optional] 
**is_default** | **bool** | Whether the file is the default file | [optional] 

## Example

```python
from openapi_client.models.get_floor_plans_success_response_result_floor_plans_floor_plan_file_attributes import GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes from a JSON string
get_floor_plans_success_response_result_floor_plans_floor_plan_file_attributes_instance = GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes.to_json())

# convert the object into a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_file_attributes_dict = get_floor_plans_success_response_result_floor_plans_floor_plan_file_attributes_instance.to_dict()
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes from a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_file_attributes_from_dict = GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes.from_dict(get_floor_plans_success_response_result_floor_plans_floor_plan_file_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



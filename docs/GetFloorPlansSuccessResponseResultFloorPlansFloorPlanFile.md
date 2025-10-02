# GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile

File related to the floor plan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_type** | **str** | Type of the file | [optional] 
**description** | **str** | Description of the file | [optional] 
**name** | **str** | Name of the file | [optional] 
**caption** | **str** | Caption of the file | [optional] 
**format** | **str** | Format of the file | [optional] 
**width** | **str** | Width of the file | [optional] 
**height** | **str** | Height of the file | [optional] 
**src** | **List[str]** | Source of the file | [optional] 
**attributes** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFileAttributes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_floor_plans_success_response_result_floor_plans_floor_plan_file import GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile from a JSON string
get_floor_plans_success_response_result_floor_plans_floor_plan_file_instance = GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile.to_json())

# convert the object into a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_file_dict = get_floor_plans_success_response_result_floor_plans_floor_plan_file_instance.to_dict()
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile from a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_file_from_dict = GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile.from_dict(get_floor_plans_success_response_result_floor_plans_floor_plan_file_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification

Identification information for the floor plan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id_value** | **str** | ID value for the floor plan | [optional] 
**attributes** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentificationAttributes**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentificationAttributes.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_floor_plans_success_response_result_floor_plans_floor_plan_identification import GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification from a JSON string
get_floor_plans_success_response_result_floor_plans_floor_plan_identification_instance = GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification.to_json())

# convert the object into a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_identification_dict = get_floor_plans_success_response_result_floor_plans_floor_plan_identification_instance.to_dict()
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification from a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_identification_from_dict = GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification.from_dict(get_floor_plans_success_response_result_floor_plans_floor_plan_identification_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



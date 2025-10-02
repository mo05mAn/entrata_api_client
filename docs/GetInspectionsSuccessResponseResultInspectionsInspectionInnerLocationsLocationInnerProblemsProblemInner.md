# GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**problem_id** | **str** | ID of the problem | 
**problem_name** | **str** | Name of the problem | 
**response** | **str** | Response to the problem | 
**sub_problems** | [**GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInnerSubProblems**](GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInnerSubProblems.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_problems_problem_inner import GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInner from a JSON string
get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_problems_problem_inner_instance = GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInner.from_json(json)
# print the JSON string representation of the object
print(GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInner.to_json())

# convert the object into a dict
get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_problems_problem_inner_dict = get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_problems_problem_inner_instance.to_dict()
# create an instance of GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInner from a dict
get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_problems_problem_inner_from_dict = GetInspectionsSuccessResponseResultInspectionsInspectionInnerLocationsLocationInnerProblemsProblemInner.from_dict(get_inspections_success_response_result_inspections_inspection_inner_locations_location_inner_problems_problem_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



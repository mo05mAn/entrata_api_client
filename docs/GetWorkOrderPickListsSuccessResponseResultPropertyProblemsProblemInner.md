# GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | ID of the problem | 
**name** | **str** | Name of the problem | 
**is_resident_portal_enabled** | **str** | Indicates if the problem is visible on the resident portal | [optional] 
**sub_maintenance_problems** | [**GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInnerSubMaintenanceProblems**](GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInnerSubMaintenanceProblems.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_work_order_pick_lists_success_response_result_property_problems_problem_inner import GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInner from a JSON string
get_work_order_pick_lists_success_response_result_property_problems_problem_inner_instance = GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInner.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInner.to_json())

# convert the object into a dict
get_work_order_pick_lists_success_response_result_property_problems_problem_inner_dict = get_work_order_pick_lists_success_response_result_property_problems_problem_inner_instance.to_dict()
# create an instance of GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInner from a dict
get_work_order_pick_lists_success_response_result_property_problems_problem_inner_from_dict = GetWorkOrderPickListsSuccessResponseResultPropertyProblemsProblemInner.from_dict(get_work_order_pick_lists_success_response_result_property_problems_problem_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



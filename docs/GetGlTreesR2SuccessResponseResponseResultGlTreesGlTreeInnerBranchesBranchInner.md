# GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranchesBranchInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**branch_id** | **str** | Unique identifier for the branch | 
**group_type** | **str** | Type of the group for the branch | 
**is_enabled** | **str** | Indicates if the branch is enabled  | [optional] 
**show_group_name** | **int** | Indicates if the group name should be displayed | [optional] 
**group_name** | **str** | The name of the group in the branch | [optional] 
**show_summary_row** | **int** | Indicates if the summary row should be shown | [optional] 
**description** | **str** | A brief description of the branch | [optional] 

## Example

```python
from openapi_client.models.get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_branches_branch_inner import GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranchesBranchInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranchesBranchInner from a JSON string
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_branches_branch_inner_instance = GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranchesBranchInner.from_json(json)
# print the JSON string representation of the object
print(GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranchesBranchInner.to_json())

# convert the object into a dict
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_branches_branch_inner_dict = get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_branches_branch_inner_instance.to_dict()
# create an instance of GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranchesBranchInner from a dict
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_branches_branch_inner_from_dict = GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranchesBranchInner.from_dict(get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_branches_branch_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



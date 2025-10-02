# GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier for the GL Tree | 
**name** | **str** | The name of the GL Tree | 
**is_master_gl_tree** | **int** | Indicates if the GL Tree is a master GL Tree (1 &#x3D; true, 0 &#x3D; false) | 
**branches** | [**GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranches**](GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerBranches.md) |  | 
**gl_accounts** | [**GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccounts**](GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccounts.md) |  | 

## Example

```python
from openapi_client.models.get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner import GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInner from a JSON string
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_instance = GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInner.from_json(json)
# print the JSON string representation of the object
print(GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInner.to_json())

# convert the object into a dict
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_dict = get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_instance.to_dict()
# create an instance of GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInner from a dict
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_from_dict = GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInner.from_dict(get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



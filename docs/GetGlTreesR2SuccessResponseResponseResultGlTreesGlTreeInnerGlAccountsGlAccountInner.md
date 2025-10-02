# GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the GL Account | 
**branch_id** | **str** | Unique identifier for the branch associated with the GL Account | 
**account_number** | **str** | Account number for the GL Account | 
**account_name** | **str** | The name of the GL Account | 
**external_id** | **str** | External identifier for the GL Account | 
**gl_group_type** | **str** | The group type to which the GL Account belongs | 
**group_location** | **str** | The location of the group for the GL Account | [optional] 
**description** | **str** | A description of the GL Account | [optional] 
**status** | **str** | The status of the GL Account (e.g., Enabled, Disabled) | 
**is_system** | **int** | Indicates if the GL Account is a system account (1 &#x3D; true, 0 &#x3D; false) | [optional] 

## Example

```python
from openapi_client.models.get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner import GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner from a JSON string
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_instance = GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner.from_json(json)
# print the JSON string representation of the object
print(GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner.to_json())

# convert the object into a dict
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_dict = get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_instance.to_dict()
# create an instance of GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner from a dict
get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_from_dict = GetGlTreesR2SuccessResponseResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner.from_dict(get_gl_trees_r2_success_response_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



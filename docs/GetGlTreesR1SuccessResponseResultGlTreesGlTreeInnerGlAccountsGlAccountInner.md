# GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | [**GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInnerAttributes**](GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInnerAttributes.md) |  | 
**account_number** | **str** | The account number. | 
**account_name** | **str** | The name of the GL account. | 
**external_id** | **str** | The external identifier for the GL account. | [optional] 
**gl_group_type** | **str** | The GL group type. | 
**group_location** | **str** | The location of the GL account group. | 
**description** | **str** | A description of the GL account. | 
**status** | **str** | The status of the GL account. | 
**is_system** | **str** | Indicates if the GL account is a system account. | 

## Example

```python
from openapi_client.models.get_gl_trees_r1_success_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner import GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner from a JSON string
get_gl_trees_r1_success_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_instance = GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner.from_json(json)
# print the JSON string representation of the object
print(GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner.to_json())

# convert the object into a dict
get_gl_trees_r1_success_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_dict = get_gl_trees_r1_success_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_instance.to_dict()
# create an instance of GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner from a dict
get_gl_trees_r1_success_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_from_dict = GetGlTreesR1SuccessResponseResultGlTreesGlTreeInnerGlAccountsGlAccountInner.from_dict(get_gl_trees_r1_success_response_result_gl_trees_gl_tree_inner_gl_accounts_gl_account_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



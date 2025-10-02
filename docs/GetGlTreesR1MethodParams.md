# GetGlTreesR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is an optional field. This field accepts single value. Property Id | [optional] 
**gl_tree_id** | **int** | This is an optional field. This field accepts single value. Gl Tree Id | [optional] 
**gl_branch_id** | **int** | This is an optional field. This field accepts single value. Gl Branch Id | [optional] 
**gl_group_type_id** | **int** | This is an optional field. This field accepts single value. Gl Group Type Id | [optional] 
**gl_tree_type_id** | **int** | This is an optional field. This field accepts single value. Gl Tree Type Id | [optional] 
**account_numbers** | **date** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 

## Example

```python
from entrata_api_client.models.get_gl_trees_r1_method_params import GetGlTreesR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTreesR1MethodParams from a JSON string
get_gl_trees_r1_method_params_instance = GetGlTreesR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(GetGlTreesR1MethodParams.to_json())

# convert the object into a dict
get_gl_trees_r1_method_params_dict = get_gl_trees_r1_method_params_instance.to_dict()
# create an instance of GetGlTreesR1MethodParams from a dict
get_gl_trees_r1_method_params_from_dict = GetGlTreesR1MethodParams.from_dict(get_gl_trees_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetJobCostBudgetsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **int** | This is a required field. This field accepts comma seperated multiple values. This node should accept property Id. | 
**job_ids** | **int** | This is a required field. This field accepts comma seperated multiple values. This node should accept property Id. | [optional] 
**job_status_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. This node should accept job status Id. | [optional] 
**ap_code_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. This node should accept apCode Id | [optional] 
**job_phase_id** | **int** | This is an optional field. This field accepts single value. This node should accept job Phase Id | [optional] 

## Example

```python
from entrata_api_client.models.get_job_cost_budgets_method_params import GetJobCostBudgetsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCostBudgetsMethodParams from a JSON string
get_job_cost_budgets_method_params_instance = GetJobCostBudgetsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetJobCostBudgetsMethodParams.to_json())

# convert the object into a dict
get_job_cost_budgets_method_params_dict = get_job_cost_budgets_method_params_instance.to_dict()
# create an instance of GetJobCostBudgetsMethodParams from a dict
get_job_cost_budgets_method_params_from_dict = GetJobCostBudgetsMethodParams.from_dict(get_job_cost_budgets_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



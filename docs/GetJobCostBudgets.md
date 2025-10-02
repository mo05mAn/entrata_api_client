# GetJobCostBudgets


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetJobCostBudgetsMethod**](GetJobCostBudgetsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_job_cost_budgets import GetJobCostBudgets

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCostBudgets from a JSON string
get_job_cost_budgets_instance = GetJobCostBudgets.from_json(json)
# print the JSON string representation of the object
print(GetJobCostBudgets.to_json())

# convert the object into a dict
get_job_cost_budgets_dict = get_job_cost_budgets_instance.to_dict()
# create an instance of GetJobCostBudgets from a dict
get_job_cost_budgets_from_dict = GetJobCostBudgets.from_dict(get_job_cost_budgets_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



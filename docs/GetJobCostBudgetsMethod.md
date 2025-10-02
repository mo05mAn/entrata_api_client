# GetJobCostBudgetsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetJobCostBudgetsMethodParams**](GetJobCostBudgetsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_job_cost_budgets_method import GetJobCostBudgetsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCostBudgetsMethod from a JSON string
get_job_cost_budgets_method_instance = GetJobCostBudgetsMethod.from_json(json)
# print the JSON string representation of the object
print(GetJobCostBudgetsMethod.to_json())

# convert the object into a dict
get_job_cost_budgets_method_dict = get_job_cost_budgets_method_instance.to_dict()
# create an instance of GetJobCostBudgetsMethod from a dict
get_job_cost_budgets_method_from_dict = GetJobCostBudgetsMethod.from_dict(get_job_cost_budgets_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



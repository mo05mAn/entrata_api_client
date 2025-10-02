# GetJobCostBudgetsSuccessResponseResultJobs


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job** | [**List[GetJobCostBudgetsSuccessResponseResultJobsJobInner]**](GetJobCostBudgetsSuccessResponseResultJobsJobInner.md) | A list of jobs. | 

## Example

```python
from entrata_api_client.models.get_job_cost_budgets_success_response_result_jobs import GetJobCostBudgetsSuccessResponseResultJobs

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCostBudgetsSuccessResponseResultJobs from a JSON string
get_job_cost_budgets_success_response_result_jobs_instance = GetJobCostBudgetsSuccessResponseResultJobs.from_json(json)
# print the JSON string representation of the object
print(GetJobCostBudgetsSuccessResponseResultJobs.to_json())

# convert the object into a dict
get_job_cost_budgets_success_response_result_jobs_dict = get_job_cost_budgets_success_response_result_jobs_instance.to_dict()
# create an instance of GetJobCostBudgetsSuccessResponseResultJobs from a dict
get_job_cost_budgets_success_response_result_jobs_from_dict = GetJobCostBudgetsSuccessResponseResultJobs.from_dict(get_job_cost_budgets_success_response_result_jobs_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



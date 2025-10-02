# GetJobCostBudgetsSuccessResponseResultJobsJobInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | The unique identifier for the property associated with the job. | 
**job_id** | **str** | The unique identifier for the job. | 
**job_status_id** | **str** | The status identifier of the job. | 
**job_phases** | [**GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhases**](GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhases.md) |  | 

## Example

```python
from entrata_api_client.models.get_job_cost_budgets_success_response_result_jobs_job_inner import GetJobCostBudgetsSuccessResponseResultJobsJobInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCostBudgetsSuccessResponseResultJobsJobInner from a JSON string
get_job_cost_budgets_success_response_result_jobs_job_inner_instance = GetJobCostBudgetsSuccessResponseResultJobsJobInner.from_json(json)
# print the JSON string representation of the object
print(GetJobCostBudgetsSuccessResponseResultJobsJobInner.to_json())

# convert the object into a dict
get_job_cost_budgets_success_response_result_jobs_job_inner_dict = get_job_cost_budgets_success_response_result_jobs_job_inner_instance.to_dict()
# create an instance of GetJobCostBudgetsSuccessResponseResultJobsJobInner from a dict
get_job_cost_budgets_success_response_result_jobs_job_inner_from_dict = GetJobCostBudgetsSuccessResponseResultJobsJobInner.from_dict(get_job_cost_budgets_success_response_result_jobs_job_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_phase_id** | **str** | The unique identifier for the job phase. | 
**job_phase_name** | **str** | The name of the job phase. | 
**ap_codes** | [**List[GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInner]**](GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInner.md) | A list of accounts payable codes associated with the job phase. | 

## Example

```python
from openapi_client.models.get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner import GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner from a JSON string
get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_instance = GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner.from_json(json)
# print the JSON string representation of the object
print(GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner.to_json())

# convert the object into a dict
get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_dict = get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_instance.to_dict()
# create an instance of GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner from a dict
get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_from_dict = GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner.from_dict(get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



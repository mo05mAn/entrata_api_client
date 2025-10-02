# GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCode


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_code_id** | **str** | The unique identifier for the AP code. | 
**ap_code_name** | **str** | The name of the AP code. | 
**unit_type_budget** | **str** | The budget for the unit type. | 
**location_budget** | **str** | The budget for the location. | 
**general_budget** | **str** | The general budget for the AP code. | 
**post_months** | [**GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCodePostMonths**](GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCodePostMonths.md) |  | 

## Example

```python
from openapi_client.models.get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_ap_codes_inner_ap_code import GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCode

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCode from a JSON string
get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_ap_codes_inner_ap_code_instance = GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCode.from_json(json)
# print the JSON string representation of the object
print(GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCode.to_json())

# convert the object into a dict
get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_ap_codes_inner_ap_code_dict = get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_ap_codes_inner_ap_code_instance.to_dict()
# create an instance of GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCode from a dict
get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_ap_codes_inner_ap_code_from_dict = GetJobCostBudgetsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInnerApCodesInnerApCode.from_dict(get_job_cost_budgets_success_response_result_jobs_job_inner_job_phases_job_phase_inner_ap_codes_inner_ap_code_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



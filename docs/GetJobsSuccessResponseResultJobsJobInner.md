# GetJobsSuccessResponseResultJobsJobInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the job. | 
**name** | **str** | The name of the job. | 
**property_id** | **str** | The unique identifier for the property associated with the job. | 
**job_category_id** | **str** | The unique identifier for the job category. | 
**gl_account_id** | **str** | The unique identifier for the general ledger account. | 
**job_status_id** | **str** | The status identifier of the job. | 
**job_status** | **str** | The current status of the job. | 
**planned_start_date** | **date** | The planned start date for the job. | 
**planned_completion_date** | **date** | The planned completion date for the job. | 
**actual_start_date** | **date** | The actual start date of the job. | 
**actual_completion_date** | **date** | The actual completion date of the job. | 
**budget_total** | **str** | The total budget for the job. | 
**job_phases** | [**GetJobsSuccessResponseResultJobsJobInnerJobPhases**](GetJobsSuccessResponseResultJobsJobInnerJobPhases.md) |  | 
**ap_contracts** | [**GetJobsSuccessResponseResultJobsJobInnerApContracts**](GetJobsSuccessResponseResultJobsJobInnerApContracts.md) |  | 

## Example

```python
from entrata_api_client.models.get_jobs_success_response_result_jobs_job_inner import GetJobsSuccessResponseResultJobsJobInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsSuccessResponseResultJobsJobInner from a JSON string
get_jobs_success_response_result_jobs_job_inner_instance = GetJobsSuccessResponseResultJobsJobInner.from_json(json)
# print the JSON string representation of the object
print(GetJobsSuccessResponseResultJobsJobInner.to_json())

# convert the object into a dict
get_jobs_success_response_result_jobs_job_inner_dict = get_jobs_success_response_result_jobs_job_inner_instance.to_dict()
# create an instance of GetJobsSuccessResponseResultJobsJobInner from a dict
get_jobs_success_response_result_jobs_job_inner_from_dict = GetJobsSuccessResponseResultJobsJobInner.from_dict(get_jobs_success_response_result_jobs_job_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



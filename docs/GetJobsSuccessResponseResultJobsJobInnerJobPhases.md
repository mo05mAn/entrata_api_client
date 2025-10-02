# GetJobsSuccessResponseResultJobsJobInnerJobPhases


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_phase** | [**List[GetJobsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner]**](GetJobsSuccessResponseResultJobsJobInnerJobPhasesJobPhaseInner.md) | A list of job phases associated with the job. | 

## Example

```python
from openapi_client.models.get_jobs_success_response_result_jobs_job_inner_job_phases import GetJobsSuccessResponseResultJobsJobInnerJobPhases

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsSuccessResponseResultJobsJobInnerJobPhases from a JSON string
get_jobs_success_response_result_jobs_job_inner_job_phases_instance = GetJobsSuccessResponseResultJobsJobInnerJobPhases.from_json(json)
# print the JSON string representation of the object
print(GetJobsSuccessResponseResultJobsJobInnerJobPhases.to_json())

# convert the object into a dict
get_jobs_success_response_result_jobs_job_inner_job_phases_dict = get_jobs_success_response_result_jobs_job_inner_job_phases_instance.to_dict()
# create an instance of GetJobsSuccessResponseResultJobsJobInnerJobPhases from a dict
get_jobs_success_response_result_jobs_job_inner_job_phases_from_dict = GetJobsSuccessResponseResultJobsJobInnerJobPhases.from_dict(get_jobs_success_response_result_jobs_job_inner_job_phases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



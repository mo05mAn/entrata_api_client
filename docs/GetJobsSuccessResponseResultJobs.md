# GetJobsSuccessResponseResultJobs


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job** | [**List[GetJobsSuccessResponseResultJobsJobInner]**](GetJobsSuccessResponseResultJobsJobInner.md) | A list of jobs. | 

## Example

```python
from entrata_api_client.models.get_jobs_success_response_result_jobs import GetJobsSuccessResponseResultJobs

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsSuccessResponseResultJobs from a JSON string
get_jobs_success_response_result_jobs_instance = GetJobsSuccessResponseResultJobs.from_json(json)
# print the JSON string representation of the object
print(GetJobsSuccessResponseResultJobs.to_json())

# convert the object into a dict
get_jobs_success_response_result_jobs_dict = get_jobs_success_response_result_jobs_instance.to_dict()
# create an instance of GetJobsSuccessResponseResultJobs from a dict
get_jobs_success_response_result_jobs_from_dict = GetJobsSuccessResponseResultJobs.from_dict(get_jobs_success_response_result_jobs_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



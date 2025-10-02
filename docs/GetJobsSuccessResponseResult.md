# GetJobsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**jobs** | [**GetJobsSuccessResponseResultJobs**](GetJobsSuccessResponseResultJobs.md) |  | 

## Example

```python
from openapi_client.models.get_jobs_success_response_result import GetJobsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsSuccessResponseResult from a JSON string
get_jobs_success_response_result_instance = GetJobsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetJobsSuccessResponseResult.to_json())

# convert the object into a dict
get_jobs_success_response_result_dict = get_jobs_success_response_result_instance.to_dict()
# create an instance of GetJobsSuccessResponseResult from a dict
get_jobs_success_response_result_from_dict = GetJobsSuccessResponseResult.from_dict(get_jobs_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



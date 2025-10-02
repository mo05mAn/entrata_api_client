# GetJobsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**GetJobsSuccessResponseResult**](GetJobsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_jobs_success_response import GetJobsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsSuccessResponse from a JSON string
get_jobs_success_response_instance = GetJobsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetJobsSuccessResponse.to_json())

# convert the object into a dict
get_jobs_success_response_dict = get_jobs_success_response_instance.to_dict()
# create an instance of GetJobsSuccessResponse from a dict
get_jobs_success_response_from_dict = GetJobsSuccessResponse.from_dict(get_jobs_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetJobs


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetJobsMethod**](GetJobsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_jobs import GetJobs

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobs from a JSON string
get_jobs_instance = GetJobs.from_json(json)
# print the JSON string representation of the object
print(GetJobs.to_json())

# convert the object into a dict
get_jobs_dict = get_jobs_instance.to_dict()
# create an instance of GetJobs from a dict
get_jobs_from_dict = GetJobs.from_dict(get_jobs_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetJobsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetJobsMethodParams**](GetJobsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_jobs_method import GetJobsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsMethod from a JSON string
get_jobs_method_instance = GetJobsMethod.from_json(json)
# print the JSON string representation of the object
print(GetJobsMethod.to_json())

# convert the object into a dict
get_jobs_method_dict = get_jobs_method_instance.to_dict()
# create an instance of GetJobsMethod from a dict
get_jobs_method_from_dict = GetJobsMethod.from_dict(get_jobs_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



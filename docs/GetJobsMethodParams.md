# GetJobsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. This node should accept the propertyId. | 
**job_category_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. This node should accept the jobCategoryIds | [optional] 
**job_status_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. This node should accept the job statusIds. | [optional] 

## Example

```python
from openapi_client.models.get_jobs_method_params import GetJobsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsMethodParams from a JSON string
get_jobs_method_params_instance = GetJobsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetJobsMethodParams.to_json())

# convert the object into a dict
get_jobs_method_params_dict = get_jobs_method_params_instance.to_dict()
# create an instance of GetJobsMethodParams from a dict
get_jobs_method_params_from_dict = GetJobsMethodParams.from_dict(get_jobs_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetJobCategoriesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gl_account_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. This is the glAccount Id associated with job category | [optional] 

## Example

```python
from openapi_client.models.get_job_categories_method_params import GetJobCategoriesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCategoriesMethodParams from a JSON string
get_job_categories_method_params_instance = GetJobCategoriesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetJobCategoriesMethodParams.to_json())

# convert the object into a dict
get_job_categories_method_params_dict = get_job_categories_method_params_instance.to_dict()
# create an instance of GetJobCategoriesMethodParams from a dict
get_job_categories_method_params_from_dict = GetJobCategoriesMethodParams.from_dict(get_job_categories_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



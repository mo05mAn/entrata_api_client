# GetJobCategoriesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetJobCategoriesMethodParams**](GetJobCategoriesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_job_categories_method import GetJobCategoriesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCategoriesMethod from a JSON string
get_job_categories_method_instance = GetJobCategoriesMethod.from_json(json)
# print the JSON string representation of the object
print(GetJobCategoriesMethod.to_json())

# convert the object into a dict
get_job_categories_method_dict = get_job_categories_method_instance.to_dict()
# create an instance of GetJobCategoriesMethod from a dict
get_job_categories_method_from_dict = GetJobCategoriesMethod.from_dict(get_job_categories_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



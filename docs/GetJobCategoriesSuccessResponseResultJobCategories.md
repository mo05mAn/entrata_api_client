# GetJobCategoriesSuccessResponseResultJobCategories


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_category** | [**List[GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner]**](GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner.md) | A list of job categories. | 

## Example

```python
from entrata_api_client.models.get_job_categories_success_response_result_job_categories import GetJobCategoriesSuccessResponseResultJobCategories

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCategoriesSuccessResponseResultJobCategories from a JSON string
get_job_categories_success_response_result_job_categories_instance = GetJobCategoriesSuccessResponseResultJobCategories.from_json(json)
# print the JSON string representation of the object
print(GetJobCategoriesSuccessResponseResultJobCategories.to_json())

# convert the object into a dict
get_job_categories_success_response_result_job_categories_dict = get_job_categories_success_response_result_job_categories_instance.to_dict()
# create an instance of GetJobCategoriesSuccessResponseResultJobCategories from a dict
get_job_categories_success_response_result_job_categories_from_dict = GetJobCategoriesSuccessResponseResultJobCategories.from_dict(get_job_categories_success_response_result_job_categories_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



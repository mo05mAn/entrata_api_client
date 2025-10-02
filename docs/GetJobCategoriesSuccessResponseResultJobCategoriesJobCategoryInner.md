# GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the job category. | 
**name** | **str** | The name of the job category. | 
**gl_account_id** | **str** | The general ledger (GL) account ID associated with the job category, if applicable. | [optional] 

## Example

```python
from openapi_client.models.get_job_categories_success_response_result_job_categories_job_category_inner import GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner from a JSON string
get_job_categories_success_response_result_job_categories_job_category_inner_instance = GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner.from_json(json)
# print the JSON string representation of the object
print(GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner.to_json())

# convert the object into a dict
get_job_categories_success_response_result_job_categories_job_category_inner_dict = get_job_categories_success_response_result_job_categories_job_category_inner_instance.to_dict()
# create an instance of GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner from a dict
get_job_categories_success_response_result_job_categories_job_category_inner_from_dict = GetJobCategoriesSuccessResponseResultJobCategoriesJobCategoryInner.from_dict(get_job_categories_success_response_result_job_categories_job_category_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



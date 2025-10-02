# GetJobCategories


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetJobCategoriesMethod**](GetJobCategoriesMethod.md) |  | 

## Example

```python
from openapi_client.models.get_job_categories import GetJobCategories

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCategories from a JSON string
get_job_categories_instance = GetJobCategories.from_json(json)
# print the JSON string representation of the object
print(GetJobCategories.to_json())

# convert the object into a dict
get_job_categories_dict = get_job_categories_instance.to_dict()
# create an instance of GetJobCategories from a dict
get_job_categories_from_dict = GetJobCategories.from_dict(get_job_categories_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



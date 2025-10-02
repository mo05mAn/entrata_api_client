# GetJobCategoriesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**GetJobCategoriesSuccessResponseResult**](GetJobCategoriesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_job_categories_success_response import GetJobCategoriesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCategoriesSuccessResponse from a JSON string
get_job_categories_success_response_instance = GetJobCategoriesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetJobCategoriesSuccessResponse.to_json())

# convert the object into a dict
get_job_categories_success_response_dict = get_job_categories_success_response_instance.to_dict()
# create an instance of GetJobCategoriesSuccessResponse from a dict
get_job_categories_success_response_from_dict = GetJobCategoriesSuccessResponse.from_dict(get_job_categories_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



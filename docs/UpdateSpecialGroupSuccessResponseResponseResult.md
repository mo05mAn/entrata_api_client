# UpdateSpecialGroupSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the operation | 
**special_group_id** | **int** | ID of the updated special group | 
**message** | **str** | Detailed message about the operation | 

## Example

```python
from openapi_client.models.update_special_group_success_response_response_result import UpdateSpecialGroupSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateSpecialGroupSuccessResponseResponseResult from a JSON string
update_special_group_success_response_response_result_instance = UpdateSpecialGroupSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateSpecialGroupSuccessResponseResponseResult.to_json())

# convert the object into a dict
update_special_group_success_response_response_result_dict = update_special_group_success_response_response_result_instance.to_dict()
# create an instance of UpdateSpecialGroupSuccessResponseResponseResult from a dict
update_special_group_success_response_response_result_from_dict = UpdateSpecialGroupSuccessResponseResponseResult.from_dict(update_special_group_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



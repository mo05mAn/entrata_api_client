# UpdateSpecialGroupSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**code** | **int** | Response code indicating success | 
**result** | [**UpdateSpecialGroupSuccessResponseResponseResult**](UpdateSpecialGroupSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_special_group_success_response_response import UpdateSpecialGroupSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateSpecialGroupSuccessResponseResponse from a JSON string
update_special_group_success_response_response_instance = UpdateSpecialGroupSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateSpecialGroupSuccessResponseResponse.to_json())

# convert the object into a dict
update_special_group_success_response_response_dict = update_special_group_success_response_response_instance.to_dict()
# create an instance of UpdateSpecialGroupSuccessResponseResponse from a dict
update_special_group_success_response_response_from_dict = UpdateSpecialGroupSuccessResponseResponse.from_dict(update_special_group_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



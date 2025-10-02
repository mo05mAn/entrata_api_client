# SendSpecialGroupSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**code** | **int** | Response code indicating success | 
**result** | [**SendSpecialGroupSuccessResponseResponseResult**](SendSpecialGroupSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_special_group_success_response_response import SendSpecialGroupSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupSuccessResponseResponse from a JSON string
send_special_group_success_response_response_instance = SendSpecialGroupSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupSuccessResponseResponse.to_json())

# convert the object into a dict
send_special_group_success_response_response_dict = send_special_group_success_response_response_instance.to_dict()
# create an instance of SendSpecialGroupSuccessResponseResponse from a dict
send_special_group_success_response_response_from_dict = SendSpecialGroupSuccessResponseResponse.from_dict(send_special_group_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



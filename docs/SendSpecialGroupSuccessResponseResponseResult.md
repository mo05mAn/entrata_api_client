# SendSpecialGroupSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the operation | 
**special_group_id** | **int** | ID of the created special group | 
**message** | **str** | Detailed message about the operation | 

## Example

```python
from entrata_api_client.models.send_special_group_success_response_response_result import SendSpecialGroupSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupSuccessResponseResponseResult from a JSON string
send_special_group_success_response_response_result_instance = SendSpecialGroupSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupSuccessResponseResponseResult.to_json())

# convert the object into a dict
send_special_group_success_response_response_result_dict = send_special_group_success_response_response_result_instance.to_dict()
# create an instance of SendSpecialGroupSuccessResponseResponseResult from a dict
send_special_group_success_response_response_result_from_dict = SendSpecialGroupSuccessResponseResponseResult.from_dict(send_special_group_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



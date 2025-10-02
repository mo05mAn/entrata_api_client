# GetCallLogsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Identifier of the request | 
**code** | **str** | Status code of the response | 
**result** | [**GetCallLogsSuccessResponseResult**](GetCallLogsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_call_logs_success_response import GetCallLogsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetCallLogsSuccessResponse from a JSON string
get_call_logs_success_response_instance = GetCallLogsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetCallLogsSuccessResponse.to_json())

# convert the object into a dict
get_call_logs_success_response_dict = get_call_logs_success_response_instance.to_dict()
# create an instance of GetCallLogsSuccessResponse from a dict
get_call_logs_success_response_from_dict = GetCallLogsSuccessResponse.from_dict(get_call_logs_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



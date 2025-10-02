# GetCallLogsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**calls** | [**GetCallLogsSuccessResponseResultCalls**](GetCallLogsSuccessResponseResultCalls.md) |  | 

## Example

```python
from openapi_client.models.get_call_logs_success_response_result import GetCallLogsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetCallLogsSuccessResponseResult from a JSON string
get_call_logs_success_response_result_instance = GetCallLogsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetCallLogsSuccessResponseResult.to_json())

# convert the object into a dict
get_call_logs_success_response_result_dict = get_call_logs_success_response_result_instance.to_dict()
# create an instance of GetCallLogsSuccessResponseResult from a dict
get_call_logs_success_response_result_from_dict = GetCallLogsSuccessResponseResult.from_dict(get_call_logs_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



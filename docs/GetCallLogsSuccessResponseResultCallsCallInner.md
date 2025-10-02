# GetCallLogsSuccessResponseResultCallsCallInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Call identifier | 
**caller_name** | **str** | Name of the caller | 
**application_id** | **str** | Application identifier | 
**origin_phone_number** | **str** | Origin phone number | 
**destination_phone_number** | **str** | Destination phone number | 
**call_type_id** | **str** | Call type identifier | 
**call_type** | **str** | Call type | 
**call_source_id** | **str** | Call source identifier | 
**call_source** | **str** | Call source | 
**call_result_id** | **str** | Call result identifier | 
**call_result** | **str** | Call result | 
**call_state** | **str** | State of the call | 
**call_analyzed** | **str** | Whether the call was analyzed | 
**property_id** | **str** | Property identifier | 
**voice_mail_type_id** | **str** | Voice mail type identifier | 
**answer_status** | **str** | Call answer status | 
**lead_source_id** | **str** | Lead source identifier | 
**lead_source_name** | **str** | Lead source name | 
**agent_name** | **str** | Agent&#39;s name | 
**call_duration** | **str** | Duration of the call | 
**call_center_talk_time** | **str** | Talk time in the call center | 

## Example

```python
from openapi_client.models.get_call_logs_success_response_result_calls_call_inner import GetCallLogsSuccessResponseResultCallsCallInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCallLogsSuccessResponseResultCallsCallInner from a JSON string
get_call_logs_success_response_result_calls_call_inner_instance = GetCallLogsSuccessResponseResultCallsCallInner.from_json(json)
# print the JSON string representation of the object
print(GetCallLogsSuccessResponseResultCallsCallInner.to_json())

# convert the object into a dict
get_call_logs_success_response_result_calls_call_inner_dict = get_call_logs_success_response_result_calls_call_inner_instance.to_dict()
# create an instance of GetCallLogsSuccessResponseResultCallsCallInner from a dict
get_call_logs_success_response_result_calls_call_inner_from_dict = GetCallLogsSuccessResponseResultCallsCallInner.from_dict(get_call_logs_success_response_result_calls_call_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



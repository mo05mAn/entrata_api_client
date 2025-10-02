# GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData

Call-specific data (only present for call events)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**call_id** | **str** | Unique identifier for the call | [optional] 
**call_from** | **str** | Phone number that initiated the call | [optional] 
**ring_through** | **str** | Phone number that received the call | [optional] 
**duration** | **str** | Duration of the call | [optional] 
**call_status** | **str** | Status of the call | [optional] 
**audio_link** | **str** | URL to the call audio recording | [optional] 

## Example

```python
from entrata_api_client.models.get_lease_activities_success_response_response_result_events_inner_call_data import GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData from a JSON string
get_lease_activities_success_response_response_result_events_inner_call_data_instance = GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData.from_json(json)
# print the JSON string representation of the object
print(GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData.to_json())

# convert the object into a dict
get_lease_activities_success_response_response_result_events_inner_call_data_dict = get_lease_activities_success_response_response_result_events_inner_call_data_instance.to_dict()
# create an instance of GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData from a dict
get_lease_activities_success_response_response_result_events_inner_call_data_from_dict = GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData.from_dict(get_lease_activities_success_response_response_result_events_inner_call_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



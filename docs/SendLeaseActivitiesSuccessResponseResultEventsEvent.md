# SendLeaseActivitiesSuccessResponseResultEventsEvent


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | Node identifier for the event | 
**lease_id** | **str** | Unique identifier for the lease | 
**status** | **str** | Status of the event insertion | 
**message** | **str** | Message detailing the event insertion result | 

## Example

```python
from openapi_client.models.send_lease_activities_success_response_result_events_event import SendLeaseActivitiesSuccessResponseResultEventsEvent

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseActivitiesSuccessResponseResultEventsEvent from a JSON string
send_lease_activities_success_response_result_events_event_instance = SendLeaseActivitiesSuccessResponseResultEventsEvent.from_json(json)
# print the JSON string representation of the object
print(SendLeaseActivitiesSuccessResponseResultEventsEvent.to_json())

# convert the object into a dict
send_lease_activities_success_response_result_events_event_dict = send_lease_activities_success_response_result_events_event_instance.to_dict()
# create an instance of SendLeaseActivitiesSuccessResponseResultEventsEvent from a dict
send_lease_activities_success_response_result_events_event_from_dict = SendLeaseActivitiesSuccessResponseResultEventsEvent.from_dict(send_lease_activities_success_response_result_events_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



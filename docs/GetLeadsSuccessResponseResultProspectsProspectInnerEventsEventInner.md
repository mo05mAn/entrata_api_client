# GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_id** | **str** | The event ID. | 
**type** | **str** | The type of event. | 
**type_id** | **str** | The event type ID. | [optional] 
**lease_id** | **str** | The lease ID. | [optional] 
**lease_interval_id** | **str** | The lease interval ID. | [optional] 
**applicant_id** | **str** | The applicant ID. | [optional] 
**comments** | **str** | Additional comments related to the event. | [optional] 
**event_reasons** | **str** | Reasons for the event. | [optional] 
**var_date** | **str** | The date of the event. | 
**appointment_date** | **str** | The appointment date. | [optional] 
**time_from** | **str** | Start time of the event. | [optional] 
**time_to** | **str** | End time of the event. | [optional] 
**event_result_id** | **str** | The event result ID. | [optional] 
**event_result** | **str** | The result of the event. | [optional] 
**call_data** | [**GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData**](GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_leads_success_response_result_prospects_prospect_inner_events_event_inner import GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInner from a JSON string
get_leads_success_response_result_prospects_prospect_inner_events_event_inner_instance = GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInner.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInner.to_json())

# convert the object into a dict
get_leads_success_response_result_prospects_prospect_inner_events_event_inner_dict = get_leads_success_response_result_prospects_prospect_inner_events_event_inner_instance.to_dict()
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInner from a dict
get_leads_success_response_result_prospects_prospect_inner_events_event_inner_from_dict = GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInner.from_dict(get_leads_success_response_result_prospects_prospect_inner_events_event_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



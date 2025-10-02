# GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_id** | **str** | The unique ID for the event. | [optional] 
**type_id** | **str** | The type ID of the event. | [optional] 
**lease_id** | **int** | The unique ID for the lease. | [optional] 
**lease_interval_id** | **int** | The lease interval ID. | [optional] 
**applicant_id** | **str** | The unique ID for the applicant. | [optional] 
**var_date** | **str** | The date of the event. | [optional] 
**type** | **str** | The type of event. | [optional] 
**appointment_date** | **str** | The scheduled appointment date. | [optional] 
**time_from** | **str** | The start time of the event. | [optional] 
**time_to** | **str** | The end time of the event. | [optional] 
**event_result_id** | **int** | The ID of the event result. | [optional] 
**event_result** | **str** | The result of the event. | [optional] 
**event_reason** | **str** | The reason for the event. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_events_success_response_result_prospects_prospect_inner_events_event_inner import GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner from a JSON string
get_lead_events_success_response_result_prospects_prospect_inner_events_event_inner_instance = GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner.from_json(json)
# print the JSON string representation of the object
print(GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner.to_json())

# convert the object into a dict
get_lead_events_success_response_result_prospects_prospect_inner_events_event_inner_dict = get_lead_events_success_response_result_prospects_prospect_inner_events_event_inner_instance.to_dict()
# create an instance of GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner from a dict
get_lead_events_success_response_result_prospects_prospect_inner_events_event_inner_from_dict = GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner.from_dict(get_lead_events_success_response_result_prospects_prospect_inner_events_event_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



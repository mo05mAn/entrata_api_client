# GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**call_id** | **str** | The call ID. | [optional] 
**call_from** | **str** | The phone number the call was from. | [optional] 
**ring_through** | **str** | The phone number that rang through. | [optional] 
**duration** | **str** | The call duration. | [optional] 
**call_status** | **str** | The status of the call. | [optional] 

## Example

```python
from openapi_client.models.get_leads_success_response_result_prospects_prospect_inner_events_event_inner_call_data import GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData from a JSON string
get_leads_success_response_result_prospects_prospect_inner_events_event_inner_call_data_instance = GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData.to_json())

# convert the object into a dict
get_leads_success_response_result_prospects_prospect_inner_events_event_inner_call_data_dict = get_leads_success_response_result_prospects_prospect_inner_events_event_inner_call_data_instance.to_dict()
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData from a dict
get_leads_success_response_result_prospects_prospect_inner_events_event_inner_call_data_from_dict = GetLeadsSuccessResponseResultProspectsProspectInnerEventsEventInnerCallData.from_dict(get_leads_success_response_result_prospects_prospect_inner_events_event_inner_call_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



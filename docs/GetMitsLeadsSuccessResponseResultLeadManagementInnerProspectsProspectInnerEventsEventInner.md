# GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_id** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInnerEventID**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInnerEventID.md) |  | [optional] 
**agent** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInnerAgent**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInnerAgent.md) |  | [optional] 
**comments** | **str** | Comments related to the event. | [optional] 
**event_reasons** | **str** | The reasons for the event. | [optional] 
**attributes** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInnerAttributes**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInnerAttributes.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_events_event_inner import GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInner from a JSON string
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_events_event_inner_instance = GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInner.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInner.to_json())

# convert the object into a dict
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_events_event_inner_dict = get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_events_event_inner_instance.to_dict()
# create an instance of GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInner from a dict
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_events_event_inner_from_dict = GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEventsEventInner.from_dict(get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_events_event_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



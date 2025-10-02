# GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents

Events associated with the prospect.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event** | [**List[GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner]**](GetLeadEventsSuccessResponseResultProspectsProspectInnerEventsEventInner.md) | A list of events related to the prospect. | [optional] 

## Example

```python
from openapi_client.models.get_lead_events_success_response_result_prospects_prospect_inner_events import GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents from a JSON string
get_lead_events_success_response_result_prospects_prospect_inner_events_instance = GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents.from_json(json)
# print the JSON string representation of the object
print(GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents.to_json())

# convert the object into a dict
get_lead_events_success_response_result_prospects_prospect_inner_events_dict = get_lead_events_success_response_result_prospects_prospect_inner_events_instance.to_dict()
# create an instance of GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents from a dict
get_lead_events_success_response_result_prospects_prospect_inner_events_from_dict = GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents.from_dict(get_lead_events_success_response_result_prospects_prospect_inner_events_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



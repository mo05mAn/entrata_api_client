# GetLeadEventsSuccessResponseResultProspectsProspectInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application_id** | **str** | The unique ID for the application. | 
**events** | [**GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents**](GetLeadEventsSuccessResponseResultProspectsProspectInnerEvents.md) |  | 

## Example

```python
from entrata_api_client.models.get_lead_events_success_response_result_prospects_prospect_inner import GetLeadEventsSuccessResponseResultProspectsProspectInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadEventsSuccessResponseResultProspectsProspectInner from a JSON string
get_lead_events_success_response_result_prospects_prospect_inner_instance = GetLeadEventsSuccessResponseResultProspectsProspectInner.from_json(json)
# print the JSON string representation of the object
print(GetLeadEventsSuccessResponseResultProspectsProspectInner.to_json())

# convert the object into a dict
get_lead_events_success_response_result_prospects_prospect_inner_dict = get_lead_events_success_response_result_prospects_prospect_inner_instance.to_dict()
# create an instance of GetLeadEventsSuccessResponseResultProspectsProspectInner from a dict
get_lead_events_success_response_result_prospects_prospect_inner_from_dict = GetLeadEventsSuccessResponseResultProspectsProspectInner.from_dict(get_lead_events_success_response_result_prospects_prospect_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



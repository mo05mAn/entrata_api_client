# GetLeadEventsSuccessResponseResultProspects

Prospects related to the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prospect** | [**List[GetLeadEventsSuccessResponseResultProspectsProspectInner]**](GetLeadEventsSuccessResponseResultProspectsProspectInner.md) | Array of prospects | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_events_success_response_result_prospects import GetLeadEventsSuccessResponseResultProspects

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadEventsSuccessResponseResultProspects from a JSON string
get_lead_events_success_response_result_prospects_instance = GetLeadEventsSuccessResponseResultProspects.from_json(json)
# print the JSON string representation of the object
print(GetLeadEventsSuccessResponseResultProspects.to_json())

# convert the object into a dict
get_lead_events_success_response_result_prospects_dict = get_lead_events_success_response_result_prospects_instance.to_dict()
# create an instance of GetLeadEventsSuccessResponseResultProspects from a dict
get_lead_events_success_response_result_prospects_from_dict = GetLeadEventsSuccessResponseResultProspects.from_dict(get_lead_events_success_response_result_prospects_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



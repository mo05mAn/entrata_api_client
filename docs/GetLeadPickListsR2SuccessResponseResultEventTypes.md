# GetLeadPickListsR2SuccessResponseResultEventTypes

The event types associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_type** | [**List[GetLeadPickListsR2SuccessResponseResultEventTypesEventTypeInner]**](GetLeadPickListsR2SuccessResponseResultEventTypesEventTypeInner.md) | A list of event types. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response_result_event_types import GetLeadPickListsR2SuccessResponseResultEventTypes

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultEventTypes from a JSON string
get_lead_pick_lists_r2_success_response_result_event_types_instance = GetLeadPickListsR2SuccessResponseResultEventTypes.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultEventTypes.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_event_types_dict = get_lead_pick_lists_r2_success_response_result_event_types_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultEventTypes from a dict
get_lead_pick_lists_r2_success_response_result_event_types_from_dict = GetLeadPickListsR2SuccessResponseResultEventTypes.from_dict(get_lead_pick_lists_r2_success_response_result_event_types_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



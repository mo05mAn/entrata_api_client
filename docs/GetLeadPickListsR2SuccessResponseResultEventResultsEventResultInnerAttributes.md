# GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInnerAttributes

Attributes related to the event result.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the event result. | [optional] 
**id** | **str** | The unique ID of the event result. | [optional] 
**event_type_id** | **str** | The ID of the related event type. | [optional] 
**default_event_result_id** | **str** | The ID of the default event result. | [optional] 
**default_event_result** | **str** | The name of the default event result. | [optional] 

## Example

```python
from openapi_client.models.get_lead_pick_lists_r2_success_response_result_event_results_event_result_inner_attributes import GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInnerAttributes from a JSON string
get_lead_pick_lists_r2_success_response_result_event_results_event_result_inner_attributes_instance = GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInnerAttributes.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_event_results_event_result_inner_attributes_dict = get_lead_pick_lists_r2_success_response_result_event_results_event_result_inner_attributes_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInnerAttributes from a dict
get_lead_pick_lists_r2_success_response_result_event_results_event_result_inner_attributes_from_dict = GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInnerAttributes.from_dict(get_lead_pick_lists_r2_success_response_result_event_results_event_result_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



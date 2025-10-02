# GetLeadPickListsR1SuccessResponseResponseResultEventResults

Event results associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_result** | [**List[GetLeadPickListsR1SuccessResponseResponseResultEventResultsEventResultInner]**](GetLeadPickListsR1SuccessResponseResponseResultEventResultsEventResultInner.md) | A list of event results. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r1_success_response_response_result_event_results import GetLeadPickListsR1SuccessResponseResponseResultEventResults

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR1SuccessResponseResponseResultEventResults from a JSON string
get_lead_pick_lists_r1_success_response_response_result_event_results_instance = GetLeadPickListsR1SuccessResponseResponseResultEventResults.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR1SuccessResponseResponseResultEventResults.to_json())

# convert the object into a dict
get_lead_pick_lists_r1_success_response_response_result_event_results_dict = get_lead_pick_lists_r1_success_response_response_result_event_results_instance.to_dict()
# create an instance of GetLeadPickListsR1SuccessResponseResponseResultEventResults from a dict
get_lead_pick_lists_r1_success_response_response_result_event_results_from_dict = GetLeadPickListsR1SuccessResponseResponseResultEventResults.from_dict(get_lead_pick_lists_r1_success_response_response_result_event_results_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetLeadPickListsR2SuccessResponseResultEventResults

Event results associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_result** | [**List[GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInner]**](GetLeadPickListsR2SuccessResponseResultEventResultsEventResultInner.md) | A list of event results. | [optional] 

## Example

```python
from openapi_client.models.get_lead_pick_lists_r2_success_response_result_event_results import GetLeadPickListsR2SuccessResponseResultEventResults

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultEventResults from a JSON string
get_lead_pick_lists_r2_success_response_result_event_results_instance = GetLeadPickListsR2SuccessResponseResultEventResults.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultEventResults.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_event_results_dict = get_lead_pick_lists_r2_success_response_result_event_results_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultEventResults from a dict
get_lead_pick_lists_r2_success_response_result_event_results_from_dict = GetLeadPickListsR2SuccessResponseResultEventResults.from_dict(get_lead_pick_lists_r2_success_response_result_event_results_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



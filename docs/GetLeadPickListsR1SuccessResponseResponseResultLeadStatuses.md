# GetLeadPickListsR1SuccessResponseResponseResultLeadStatuses

Lead statuses associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lead_status** | [**List[GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInner]**](GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInner.md) | A list of lead statuses. | [optional] 

## Example

```python
from openapi_client.models.get_lead_pick_lists_r1_success_response_response_result_lead_statuses import GetLeadPickListsR1SuccessResponseResponseResultLeadStatuses

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR1SuccessResponseResponseResultLeadStatuses from a JSON string
get_lead_pick_lists_r1_success_response_response_result_lead_statuses_instance = GetLeadPickListsR1SuccessResponseResponseResultLeadStatuses.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR1SuccessResponseResponseResultLeadStatuses.to_json())

# convert the object into a dict
get_lead_pick_lists_r1_success_response_response_result_lead_statuses_dict = get_lead_pick_lists_r1_success_response_response_result_lead_statuses_instance.to_dict()
# create an instance of GetLeadPickListsR1SuccessResponseResponseResultLeadStatuses from a dict
get_lead_pick_lists_r1_success_response_response_result_lead_statuses_from_dict = GetLeadPickListsR1SuccessResponseResponseResultLeadStatuses.from_dict(get_lead_pick_lists_r1_success_response_response_result_lead_statuses_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



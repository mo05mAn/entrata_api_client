# GetLeadPickListsR2SuccessResponseResultLeadStatuses

Lead statuses associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lead_status** | [**List[GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInner]**](GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInner.md) | A list of lead statuses. | [optional] 

## Example

```python
from openapi_client.models.get_lead_pick_lists_r2_success_response_result_lead_statuses import GetLeadPickListsR2SuccessResponseResultLeadStatuses

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultLeadStatuses from a JSON string
get_lead_pick_lists_r2_success_response_result_lead_statuses_instance = GetLeadPickListsR2SuccessResponseResultLeadStatuses.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultLeadStatuses.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_lead_statuses_dict = get_lead_pick_lists_r2_success_response_result_lead_statuses_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultLeadStatuses from a dict
get_lead_pick_lists_r2_success_response_result_lead_statuses_from_dict = GetLeadPickListsR2SuccessResponseResultLeadStatuses.from_dict(get_lead_pick_lists_r2_success_response_result_lead_statuses_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



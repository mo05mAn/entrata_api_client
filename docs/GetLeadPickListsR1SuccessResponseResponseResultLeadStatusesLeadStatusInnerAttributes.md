# GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInnerAttributes

Attributes related to the lead status.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique ID for the lead status. | [optional] 
**name** | **str** | The name of the lead status. | [optional] 
**lease_interval_type_name** | **str** | The type of lease interval. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r1_success_response_response_result_lead_statuses_lead_status_inner_attributes import GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInnerAttributes from a JSON string
get_lead_pick_lists_r1_success_response_response_result_lead_statuses_lead_status_inner_attributes_instance = GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInnerAttributes.to_json())

# convert the object into a dict
get_lead_pick_lists_r1_success_response_response_result_lead_statuses_lead_status_inner_attributes_dict = get_lead_pick_lists_r1_success_response_response_result_lead_statuses_lead_status_inner_attributes_instance.to_dict()
# create an instance of GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInnerAttributes from a dict
get_lead_pick_lists_r1_success_response_response_result_lead_statuses_lead_status_inner_attributes_from_dict = GetLeadPickListsR1SuccessResponseResponseResultLeadStatusesLeadStatusInnerAttributes.from_dict(get_lead_pick_lists_r1_success_response_response_result_lead_statuses_lead_status_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



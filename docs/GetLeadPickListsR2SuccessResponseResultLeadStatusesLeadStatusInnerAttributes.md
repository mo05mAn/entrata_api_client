# GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInnerAttributes

Attributes related to the lead status.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique ID of the lead status. | [optional] 
**name** | **str** | The name of the lead status. | [optional] 
**lease_interval_type_name** | **str** | The type of lease interval. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response_result_lead_statuses_lead_status_inner_attributes import GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInnerAttributes from a JSON string
get_lead_pick_lists_r2_success_response_result_lead_statuses_lead_status_inner_attributes_instance = GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInnerAttributes.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_lead_statuses_lead_status_inner_attributes_dict = get_lead_pick_lists_r2_success_response_result_lead_statuses_lead_status_inner_attributes_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInnerAttributes from a dict
get_lead_pick_lists_r2_success_response_result_lead_statuses_lead_status_inner_attributes_from_dict = GetLeadPickListsR2SuccessResponseResultLeadStatusesLeadStatusInnerAttributes.from_dict(get_lead_pick_lists_r2_success_response_result_lead_statuses_lead_status_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



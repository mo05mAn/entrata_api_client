# GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents

Leasing agents associated with the property.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**leasing_agent** | [**List[GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgentsLeasingAgentInner]**](GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgentsLeasingAgentInner.md) | A list of leasing agents. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response_result_property_leasing_agents import GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents from a JSON string
get_lead_pick_lists_r2_success_response_result_property_leasing_agents_instance = GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_property_leasing_agents_dict = get_lead_pick_lists_r2_success_response_result_property_leasing_agents_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents from a dict
get_lead_pick_lists_r2_success_response_result_property_leasing_agents_from_dict = GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents.from_dict(get_lead_pick_lists_r2_success_response_result_property_leasing_agents_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



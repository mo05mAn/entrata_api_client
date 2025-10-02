# GetLeadPickListsR2SuccessResponseResultProperty

The property data associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**leasing_agents** | [**GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents**](GetLeadPickListsR2SuccessResponseResultPropertyLeasingAgents.md) |  | [optional] 
**quote_provisions** | [**GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions**](GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions.md) |  | [optional] 
**attributes** | [**GetLeadPickListsR2SuccessResponseResultPropertyAttributes**](GetLeadPickListsR2SuccessResponseResultPropertyAttributes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response_result_property import GetLeadPickListsR2SuccessResponseResultProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultProperty from a JSON string
get_lead_pick_lists_r2_success_response_result_property_instance = GetLeadPickListsR2SuccessResponseResultProperty.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultProperty.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_property_dict = get_lead_pick_lists_r2_success_response_result_property_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultProperty from a dict
get_lead_pick_lists_r2_success_response_result_property_from_dict = GetLeadPickListsR2SuccessResponseResultProperty.from_dict(get_lead_pick_lists_r2_success_response_result_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetLeadPickListsR2SuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_types** | [**GetLeadPickListsR2SuccessResponseResultEventTypes**](GetLeadPickListsR2SuccessResponseResultEventTypes.md) |  | [optional] 
**event_sub_types** | [**GetLeadPickListsR2SuccessResponseResultEventSubTypes**](GetLeadPickListsR2SuccessResponseResultEventSubTypes.md) |  | [optional] 
**var_property** | [**GetLeadPickListsR2SuccessResponseResultProperty**](GetLeadPickListsR2SuccessResponseResultProperty.md) |  | [optional] 
**event_results** | [**GetLeadPickListsR2SuccessResponseResultEventResults**](GetLeadPickListsR2SuccessResponseResultEventResults.md) |  | [optional] 
**lead_statuses** | [**GetLeadPickListsR2SuccessResponseResultLeadStatuses**](GetLeadPickListsR2SuccessResponseResultLeadStatuses.md) |  | [optional] 
**ps_products** | [**GetLeadPickListsR2SuccessResponseResultPsProducts**](GetLeadPickListsR2SuccessResponseResultPsProducts.md) |  | [optional] 
**list_item_types** | [**GetLeadPickListsR2SuccessResponseResultListItemTypes**](GetLeadPickListsR2SuccessResponseResultListItemTypes.md) |  | [optional] 
**customer_relationship_types** | [**GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes**](GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response_result import GetLeadPickListsR2SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResult from a JSON string
get_lead_pick_lists_r2_success_response_result_instance = GetLeadPickListsR2SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResult.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_dict = get_lead_pick_lists_r2_success_response_result_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResult from a dict
get_lead_pick_lists_r2_success_response_result_from_dict = GetLeadPickListsR2SuccessResponseResult.from_dict(get_lead_pick_lists_r2_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



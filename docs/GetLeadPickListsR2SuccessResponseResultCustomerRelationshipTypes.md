# GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes

Customer relationship types associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_relationship_type** | [**List[GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInner]**](GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInner.md) | A list of customer relationship types. | [optional] 

## Example

```python
from openapi_client.models.get_lead_pick_lists_r2_success_response_result_customer_relationship_types import GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes from a JSON string
get_lead_pick_lists_r2_success_response_result_customer_relationship_types_instance = GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_customer_relationship_types_dict = get_lead_pick_lists_r2_success_response_result_customer_relationship_types_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes from a dict
get_lead_pick_lists_r2_success_response_result_customer_relationship_types_from_dict = GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypes.from_dict(get_lead_pick_lists_r2_success_response_result_customer_relationship_types_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



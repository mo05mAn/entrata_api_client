# GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInnerAttributes

Attributes related to the customer relationship type.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique ID of the customer relationship type. | [optional] 
**name** | **str** | The name of the customer relationship type. | [optional] 
**is_default** | **str** | Indicates if the customer relationship type is the default. | [optional] 
**customer_type** | **str** | The type of customer. | [optional] 
**customer_type_id** | **str** | The unique ID of the customer type. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response_result_customer_relationship_types_customer_relationship_type_inner_attributes import GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInnerAttributes from a JSON string
get_lead_pick_lists_r2_success_response_result_customer_relationship_types_customer_relationship_type_inner_attributes_instance = GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInnerAttributes.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_customer_relationship_types_customer_relationship_type_inner_attributes_dict = get_lead_pick_lists_r2_success_response_result_customer_relationship_types_customer_relationship_type_inner_attributes_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInnerAttributes from a dict
get_lead_pick_lists_r2_success_response_result_customer_relationship_types_customer_relationship_type_inner_attributes_from_dict = GetLeadPickListsR2SuccessResponseResultCustomerRelationshipTypesCustomerRelationshipTypeInnerAttributes.from_dict(get_lead_pick_lists_r2_success_response_result_customer_relationship_types_customer_relationship_type_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



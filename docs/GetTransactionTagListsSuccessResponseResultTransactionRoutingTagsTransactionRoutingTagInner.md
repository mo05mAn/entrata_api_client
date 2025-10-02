# GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the routing tag. | 
**name** | **str** | The name of the routing tag. | 
**description** | **str** | The description of the routing tag. | [optional] 
**is_published** | **int** | Indicates whether the routing tag is published. | 

## Example

```python
from openapi_client.models.get_transaction_tag_lists_success_response_result_transaction_routing_tags_transaction_routing_tag_inner import GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner from a JSON string
get_transaction_tag_lists_success_response_result_transaction_routing_tags_transaction_routing_tag_inner_instance = GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner.from_json(json)
# print the JSON string representation of the object
print(GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner.to_json())

# convert the object into a dict
get_transaction_tag_lists_success_response_result_transaction_routing_tags_transaction_routing_tag_inner_dict = get_transaction_tag_lists_success_response_result_transaction_routing_tags_transaction_routing_tag_inner_instance.to_dict()
# create an instance of GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner from a dict
get_transaction_tag_lists_success_response_result_transaction_routing_tags_transaction_routing_tag_inner_from_dict = GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner.from_dict(get_transaction_tag_lists_success_response_result_transaction_routing_tags_transaction_routing_tag_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



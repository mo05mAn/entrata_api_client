# GetTransactionTagListsSuccessResponseResultTransactionRoutingTags


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transaction_routing_tag** | [**List[GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner]**](GetTransactionTagListsSuccessResponseResultTransactionRoutingTagsTransactionRoutingTagInner.md) | A list of transaction routing tags. | 

## Example

```python
from openapi_client.models.get_transaction_tag_lists_success_response_result_transaction_routing_tags import GetTransactionTagListsSuccessResponseResultTransactionRoutingTags

# TODO update the JSON string below
json = "{}"
# create an instance of GetTransactionTagListsSuccessResponseResultTransactionRoutingTags from a JSON string
get_transaction_tag_lists_success_response_result_transaction_routing_tags_instance = GetTransactionTagListsSuccessResponseResultTransactionRoutingTags.from_json(json)
# print the JSON string representation of the object
print(GetTransactionTagListsSuccessResponseResultTransactionRoutingTags.to_json())

# convert the object into a dict
get_transaction_tag_lists_success_response_result_transaction_routing_tags_dict = get_transaction_tag_lists_success_response_result_transaction_routing_tags_instance.to_dict()
# create an instance of GetTransactionTagListsSuccessResponseResultTransactionRoutingTags from a dict
get_transaction_tag_lists_success_response_result_transaction_routing_tags_from_dict = GetTransactionTagListsSuccessResponseResultTransactionRoutingTags.from_dict(get_transaction_tag_lists_success_response_result_transaction_routing_tags_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



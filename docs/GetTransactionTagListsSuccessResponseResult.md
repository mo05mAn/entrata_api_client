# GetTransactionTagListsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transaction_custom_tags** | [**GetTransactionTagListsSuccessResponseResultTransactionCustomTags**](GetTransactionTagListsSuccessResponseResultTransactionCustomTags.md) |  | 
**transaction_routing_tags** | [**GetTransactionTagListsSuccessResponseResultTransactionRoutingTags**](GetTransactionTagListsSuccessResponseResultTransactionRoutingTags.md) |  | 

## Example

```python
from openapi_client.models.get_transaction_tag_lists_success_response_result import GetTransactionTagListsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetTransactionTagListsSuccessResponseResult from a JSON string
get_transaction_tag_lists_success_response_result_instance = GetTransactionTagListsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetTransactionTagListsSuccessResponseResult.to_json())

# convert the object into a dict
get_transaction_tag_lists_success_response_result_dict = get_transaction_tag_lists_success_response_result_instance.to_dict()
# create an instance of GetTransactionTagListsSuccessResponseResult from a dict
get_transaction_tag_lists_success_response_result_from_dict = GetTransactionTagListsSuccessResponseResult.from_dict(get_transaction_tag_lists_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



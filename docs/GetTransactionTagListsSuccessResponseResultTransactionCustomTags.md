# GetTransactionTagListsSuccessResponseResultTransactionCustomTags


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transaction_custom_tag** | [**List[GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner]**](GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner.md) | A list of transaction custom tags. | 

## Example

```python
from openapi_client.models.get_transaction_tag_lists_success_response_result_transaction_custom_tags import GetTransactionTagListsSuccessResponseResultTransactionCustomTags

# TODO update the JSON string below
json = "{}"
# create an instance of GetTransactionTagListsSuccessResponseResultTransactionCustomTags from a JSON string
get_transaction_tag_lists_success_response_result_transaction_custom_tags_instance = GetTransactionTagListsSuccessResponseResultTransactionCustomTags.from_json(json)
# print the JSON string representation of the object
print(GetTransactionTagListsSuccessResponseResultTransactionCustomTags.to_json())

# convert the object into a dict
get_transaction_tag_lists_success_response_result_transaction_custom_tags_dict = get_transaction_tag_lists_success_response_result_transaction_custom_tags_instance.to_dict()
# create an instance of GetTransactionTagListsSuccessResponseResultTransactionCustomTags from a dict
get_transaction_tag_lists_success_response_result_transaction_custom_tags_from_dict = GetTransactionTagListsSuccessResponseResultTransactionCustomTags.from_dict(get_transaction_tag_lists_success_response_result_transaction_custom_tags_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



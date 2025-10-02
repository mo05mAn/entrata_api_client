# GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the custom tag. | 
**name** | **str** | The name of the custom tag. | 
**code** | **str** | The code associated with the custom tag. | [optional] 
**description** | **str** | The description of the custom tag. | [optional] 
**is_published** | **int** | Indicates whether the custom tag is published. | 

## Example

```python
from entrata_api_client.models.get_transaction_tag_lists_success_response_result_transaction_custom_tags_transaction_custom_tag_inner import GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner from a JSON string
get_transaction_tag_lists_success_response_result_transaction_custom_tags_transaction_custom_tag_inner_instance = GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner.from_json(json)
# print the JSON string representation of the object
print(GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner.to_json())

# convert the object into a dict
get_transaction_tag_lists_success_response_result_transaction_custom_tags_transaction_custom_tag_inner_dict = get_transaction_tag_lists_success_response_result_transaction_custom_tags_transaction_custom_tag_inner_instance.to_dict()
# create an instance of GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner from a dict
get_transaction_tag_lists_success_response_result_transaction_custom_tags_transaction_custom_tag_inner_from_dict = GetTransactionTagListsSuccessResponseResultTransactionCustomTagsTransactionCustomTagInner.from_dict(get_transaction_tag_lists_success_response_result_transaction_custom_tags_transaction_custom_tag_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



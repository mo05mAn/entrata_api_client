# GetTransactionTagListsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**GetTransactionTagListsSuccessResponseResult**](GetTransactionTagListsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_transaction_tag_lists_success_response import GetTransactionTagListsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetTransactionTagListsSuccessResponse from a JSON string
get_transaction_tag_lists_success_response_instance = GetTransactionTagListsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetTransactionTagListsSuccessResponse.to_json())

# convert the object into a dict
get_transaction_tag_lists_success_response_dict = get_transaction_tag_lists_success_response_instance.to_dict()
# create an instance of GetTransactionTagListsSuccessResponse from a dict
get_transaction_tag_lists_success_response_from_dict = GetTransactionTagListsSuccessResponse.from_dict(get_transaction_tag_lists_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



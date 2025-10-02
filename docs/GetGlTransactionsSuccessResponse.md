# GetGlTransactionsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**result** | [**GetGlTransactionsSuccessResponseResult**](GetGlTransactionsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_gl_transactions_success_response import GetGlTransactionsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsSuccessResponse from a JSON string
get_gl_transactions_success_response_instance = GetGlTransactionsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsSuccessResponse.to_json())

# convert the object into a dict
get_gl_transactions_success_response_dict = get_gl_transactions_success_response_instance.to_dict()
# create an instance of GetGlTransactionsSuccessResponse from a dict
get_gl_transactions_success_response_from_dict = GetGlTransactionsSuccessResponse.from_dict(get_gl_transactions_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



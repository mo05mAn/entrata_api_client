# GetQuotesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response code indicating the result. | 
**result** | [**GetQuotesSuccessResponseResult**](GetQuotesSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_quotes_success_response import GetQuotesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponse from a JSON string
get_quotes_success_response_instance = GetQuotesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponse.to_json())

# convert the object into a dict
get_quotes_success_response_dict = get_quotes_success_response_instance.to_dict()
# create an instance of GetQuotesSuccessResponse from a dict
get_quotes_success_response_from_dict = GetQuotesSuccessResponse.from_dict(get_quotes_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



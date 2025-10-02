# ApplyQuoteSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response code indicating the result. | 
**result** | [**ApplyQuoteSuccessResponseResult**](ApplyQuoteSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.apply_quote_success_response import ApplyQuoteSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of ApplyQuoteSuccessResponse from a JSON string
apply_quote_success_response_instance = ApplyQuoteSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(ApplyQuoteSuccessResponse.to_json())

# convert the object into a dict
apply_quote_success_response_dict = apply_quote_success_response_instance.to_dict()
# create an instance of ApplyQuoteSuccessResponse from a dict
apply_quote_success_response_from_dict = ApplyQuoteSuccessResponse.from_dict(apply_quote_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



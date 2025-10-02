# ApplyQuoteSuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | The status of the request. | [optional] 
**quote_id** | **str** | The unique ID of the quote. | [optional] 
**message** | **str** | Message providing additional details about the result. | [optional] 

## Example

```python
from openapi_client.models.apply_quote_success_response_result import ApplyQuoteSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of ApplyQuoteSuccessResponseResult from a JSON string
apply_quote_success_response_result_instance = ApplyQuoteSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(ApplyQuoteSuccessResponseResult.to_json())

# convert the object into a dict
apply_quote_success_response_result_dict = apply_quote_success_response_result_instance.to_dict()
# create an instance of ApplyQuoteSuccessResponseResult from a dict
apply_quote_success_response_result_from_dict = ApplyQuoteSuccessResponseResult.from_dict(apply_quote_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



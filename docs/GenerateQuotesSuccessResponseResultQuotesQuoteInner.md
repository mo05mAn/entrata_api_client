# GenerateQuotesSuccessResponseResultQuotesQuoteInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | The identifier for the quote node. | [optional] 
**status** | **str** | The status of the quote generation. | [optional] 
**quote_id** | **str** | The unique ID for the quote. | [optional] 
**message** | **str** | Message providing additional details about the quote. | [optional] 

## Example

```python
from openapi_client.models.generate_quotes_success_response_result_quotes_quote_inner import GenerateQuotesSuccessResponseResultQuotesQuoteInner

# TODO update the JSON string below
json = "{}"
# create an instance of GenerateQuotesSuccessResponseResultQuotesQuoteInner from a JSON string
generate_quotes_success_response_result_quotes_quote_inner_instance = GenerateQuotesSuccessResponseResultQuotesQuoteInner.from_json(json)
# print the JSON string representation of the object
print(GenerateQuotesSuccessResponseResultQuotesQuoteInner.to_json())

# convert the object into a dict
generate_quotes_success_response_result_quotes_quote_inner_dict = generate_quotes_success_response_result_quotes_quote_inner_instance.to_dict()
# create an instance of GenerateQuotesSuccessResponseResultQuotesQuoteInner from a dict
generate_quotes_success_response_result_quotes_quote_inner_from_dict = GenerateQuotesSuccessResponseResultQuotesQuoteInner.from_dict(generate_quotes_success_response_result_quotes_quote_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



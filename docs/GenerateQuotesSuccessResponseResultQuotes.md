# GenerateQuotesSuccessResponseResultQuotes

The quotes associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**quote** | [**List[GenerateQuotesSuccessResponseResultQuotesQuoteInner]**](GenerateQuotesSuccessResponseResultQuotesQuoteInner.md) | A list of quotes. | [optional] 

## Example

```python
from entrata_api_client.models.generate_quotes_success_response_result_quotes import GenerateQuotesSuccessResponseResultQuotes

# TODO update the JSON string below
json = "{}"
# create an instance of GenerateQuotesSuccessResponseResultQuotes from a JSON string
generate_quotes_success_response_result_quotes_instance = GenerateQuotesSuccessResponseResultQuotes.from_json(json)
# print the JSON string representation of the object
print(GenerateQuotesSuccessResponseResultQuotes.to_json())

# convert the object into a dict
generate_quotes_success_response_result_quotes_dict = generate_quotes_success_response_result_quotes_instance.to_dict()
# create an instance of GenerateQuotesSuccessResponseResultQuotes from a dict
generate_quotes_success_response_result_quotes_from_dict = GenerateQuotesSuccessResponseResultQuotes.from_dict(generate_quotes_success_response_result_quotes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



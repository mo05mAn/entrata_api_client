# GenerateQuotesSuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**quotes** | [**GenerateQuotesSuccessResponseResultQuotes**](GenerateQuotesSuccessResponseResultQuotes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.generate_quotes_success_response_result import GenerateQuotesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GenerateQuotesSuccessResponseResult from a JSON string
generate_quotes_success_response_result_instance = GenerateQuotesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GenerateQuotesSuccessResponseResult.to_json())

# convert the object into a dict
generate_quotes_success_response_result_dict = generate_quotes_success_response_result_instance.to_dict()
# create an instance of GenerateQuotesSuccessResponseResult from a dict
generate_quotes_success_response_result_from_dict = GenerateQuotesSuccessResponseResult.from_dict(generate_quotes_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



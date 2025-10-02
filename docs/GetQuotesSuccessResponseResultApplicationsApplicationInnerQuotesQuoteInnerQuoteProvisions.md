# GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions

The provisions or discounts available for the quote.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**quote_provision** | [**List[GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisionsQuoteProvisionInner]**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisionsQuoteProvisionInner.md) | A list of quote provisions. | [optional] 

## Example

```python
from openapi_client.models.get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_quote_provisions import GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions from a JSON string
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_quote_provisions_instance = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_quote_provisions_dict = get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_quote_provisions_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions from a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_quote_provisions_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions.from_dict(get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_quote_provisions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



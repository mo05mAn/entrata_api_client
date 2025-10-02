# GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms

The lease terms for the quote.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_term** | [**List[GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTermsLeaseTermInner]**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTermsLeaseTermInner.md) | A list of lease terms. | [optional] 

## Example

```python
from entrata_api_client.models.get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_lease_terms import GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms from a JSON string
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_lease_terms_instance = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_lease_terms_dict = get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_lease_terms_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms from a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_lease_terms_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms.from_dict(get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_lease_terms_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



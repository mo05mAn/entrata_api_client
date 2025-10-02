# GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes

The list of quotes associated with the application.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**quote** | [**List[GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner]**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner.md) | A list of quotes. | [optional] 

## Example

```python
from openapi_client.models.get_quotes_success_response_result_applications_application_inner_quotes import GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes from a JSON string
get_quotes_success_response_result_applications_application_inner_quotes_instance = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_quotes_dict = get_quotes_success_response_result_applications_application_inner_quotes_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes from a dict
get_quotes_success_response_result_applications_application_inner_quotes_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes.from_dict(get_quotes_success_response_result_applications_application_inner_quotes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



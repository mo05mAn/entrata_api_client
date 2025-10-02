# GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets

The list of pets allowed with the lease.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pet** | [**List[GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPetsPetInner]**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPetsPetInner.md) | A list of pets. | [optional] 

## Example

```python
from entrata_api_client.models.get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_pets import GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets from a JSON string
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_pets_instance = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_pets_dict = get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_pets_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets from a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_pets_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets.from_dict(get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_pets_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



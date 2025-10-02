# GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges

The list of charges associated with the lease.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**charge** | [**List[GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner]**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerChargesChargeInner.md) | A list of charges. | [optional] 

## Example

```python
from openapi_client.models.get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges import GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges from a JSON string
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_instance = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_dict = get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges from a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges.from_dict(get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_charges_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



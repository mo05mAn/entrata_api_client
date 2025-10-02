# GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the quote. | [optional] 
**move_in_date** | **str** | The move-in date for the quoted lease. | [optional] 
**created_on** | **str** | The date and time when the quote was created. | [optional] 
**accepted_on** | **str** | The date when the quote was accepted. | [optional] 
**expires_on** | **str** | The expiration date of the quote. | [optional] 
**is_selected** | **str** | Indicates whether the quote is selected. | [optional] 
**building_id** | **str** | The unique identifier for the building. | [optional] 
**building_name** | **str** | The name of the building. | [optional] 
**floor_plan_id** | **str** | The unique identifier for the floor plan. | [optional] 
**floor_plan_name** | **str** | The name of the floor plan. | [optional] 
**unit_number** | **str** | The unit number for the quoted lease. | [optional] 
**number_of_bed_rooms** | **str** | The number of bedrooms in the unit. | [optional] 
**number_of_bath_rooms** | **str** | The number of bathrooms in the unit. | [optional] 
**lease_terms** | [**GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerLeaseTerms.md) |  | [optional] 
**quote_provisions** | [**GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerQuoteProvisions.md) |  | [optional] 
**optional_items** | [**GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerOptionalItems**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerOptionalItems.md) |  | [optional] 
**services** | [**GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServices**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServices.md) |  | [optional] 
**pets** | [**GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerPets.md) |  | [optional] 
**charges** | [**GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerCharges.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_quotes_success_response_result_applications_application_inner_quotes_quote_inner import GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner from a JSON string
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_instance = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_dict = get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner from a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInner.from_dict(get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



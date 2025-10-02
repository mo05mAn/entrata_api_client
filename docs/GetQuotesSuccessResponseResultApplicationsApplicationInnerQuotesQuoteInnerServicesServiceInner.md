# GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServicesServiceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**add_on_type_id** | **str** | The unique identifier for the add-on service. | [optional] 
**name** | **str** | The name of the service. | [optional] 
**type** | **str** | The type of the service. | [optional] 
**current_rate** | **str** | The current rate for the service. | [optional] 
**deposit** | **str** | The deposit for the service. | [optional] 
**reservation_fee** | **str** | The reservation fee for the service. | [optional] 

## Example

```python
from openapi_client.models.get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_services_service_inner import GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServicesServiceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServicesServiceInner from a JSON string
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_services_service_inner_instance = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServicesServiceInner.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServicesServiceInner.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_services_service_inner_dict = get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_services_service_inner_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServicesServiceInner from a dict
get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_services_service_inner_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotesQuoteInnerServicesServiceInner.from_dict(get_quotes_success_response_result_applications_application_inner_quotes_quote_inner_services_service_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



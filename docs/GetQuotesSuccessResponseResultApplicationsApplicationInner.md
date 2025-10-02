# GetQuotesSuccessResponseResultApplicationsApplicationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application_id** | **str** | The unique identifier for the application. | [optional] 
**application_status_id** | **str** | The status ID of the application. | [optional] 
**application_status** | **str** | The status of the application. | [optional] 
**quotes** | [**GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes**](GetQuotesSuccessResponseResultApplicationsApplicationInnerQuotes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_quotes_success_response_result_applications_application_inner import GetQuotesSuccessResponseResultApplicationsApplicationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInner from a JSON string
get_quotes_success_response_result_applications_application_inner_instance = GetQuotesSuccessResponseResultApplicationsApplicationInner.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplicationsApplicationInner.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_application_inner_dict = get_quotes_success_response_result_applications_application_inner_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplicationsApplicationInner from a dict
get_quotes_success_response_result_applications_application_inner_from_dict = GetQuotesSuccessResponseResultApplicationsApplicationInner.from_dict(get_quotes_success_response_result_applications_application_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



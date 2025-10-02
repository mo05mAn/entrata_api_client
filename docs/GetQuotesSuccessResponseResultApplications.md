# GetQuotesSuccessResponseResultApplications

The applications associated with the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application** | [**List[GetQuotesSuccessResponseResultApplicationsApplicationInner]**](GetQuotesSuccessResponseResultApplicationsApplicationInner.md) | A list of application entries. | [optional] 

## Example

```python
from entrata_api_client.models.get_quotes_success_response_result_applications import GetQuotesSuccessResponseResultApplications

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResultApplications from a JSON string
get_quotes_success_response_result_applications_instance = GetQuotesSuccessResponseResultApplications.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResultApplications.to_json())

# convert the object into a dict
get_quotes_success_response_result_applications_dict = get_quotes_success_response_result_applications_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResultApplications from a dict
get_quotes_success_response_result_applications_from_dict = GetQuotesSuccessResponseResultApplications.from_dict(get_quotes_success_response_result_applications_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



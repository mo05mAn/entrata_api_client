# GetQuotesSuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency_code** | **str** | The currency code used in the request. | [optional] 
**applications** | [**GetQuotesSuccessResponseResultApplications**](GetQuotesSuccessResponseResultApplications.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_quotes_success_response_result import GetQuotesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetQuotesSuccessResponseResult from a JSON string
get_quotes_success_response_result_instance = GetQuotesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetQuotesSuccessResponseResult.to_json())

# convert the object into a dict
get_quotes_success_response_result_dict = get_quotes_success_response_result_instance.to_dict()
# create an instance of GetQuotesSuccessResponseResult from a dict
get_quotes_success_response_result_from_dict = GetQuotesSuccessResponseResult.from_dict(get_quotes_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



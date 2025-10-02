# SearchCustomersSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customers** | [**SearchCustomersSuccessResponseResultCustomers**](SearchCustomersSuccessResponseResultCustomers.md) |  | 

## Example

```python
from openapi_client.models.search_customers_success_response_result import SearchCustomersSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCustomersSuccessResponseResult from a JSON string
search_customers_success_response_result_instance = SearchCustomersSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SearchCustomersSuccessResponseResult.to_json())

# convert the object into a dict
search_customers_success_response_result_dict = search_customers_success_response_result_instance.to_dict()
# create an instance of SearchCustomersSuccessResponseResult from a dict
search_customers_success_response_result_from_dict = SearchCustomersSuccessResponseResult.from_dict(search_customers_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



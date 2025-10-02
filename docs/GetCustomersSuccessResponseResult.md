# GetCustomersSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customers** | [**GetCustomersSuccessResponseResultCustomers**](GetCustomersSuccessResponseResultCustomers.md) |  | 

## Example

```python
from openapi_client.models.get_customers_success_response_result import GetCustomersSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomersSuccessResponseResult from a JSON string
get_customers_success_response_result_instance = GetCustomersSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetCustomersSuccessResponseResult.to_json())

# convert the object into a dict
get_customers_success_response_result_dict = get_customers_success_response_result_instance.to_dict()
# create an instance of GetCustomersSuccessResponseResult from a dict
get_customers_success_response_result_from_dict = GetCustomersSuccessResponseResult.from_dict(get_customers_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# UpdateCustomersSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customers** | [**UpdateCustomersSuccessResponseResultCustomers**](UpdateCustomersSuccessResponseResultCustomers.md) |  | 

## Example

```python
from openapi_client.models.update_customers_success_response_result import UpdateCustomersSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomersSuccessResponseResult from a JSON string
update_customers_success_response_result_instance = UpdateCustomersSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomersSuccessResponseResult.to_json())

# convert the object into a dict
update_customers_success_response_result_dict = update_customers_success_response_result_instance.to_dict()
# create an instance of UpdateCustomersSuccessResponseResult from a dict
update_customers_success_response_result_from_dict = UpdateCustomersSuccessResponseResult.from_dict(update_customers_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



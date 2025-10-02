# UpdateCustomersSuccessResponseResultCustomers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer** | [**List[UpdateCustomersSuccessResponseResultCustomersCustomerInner]**](UpdateCustomersSuccessResponseResultCustomersCustomerInner.md) |  | 

## Example

```python
from openapi_client.models.update_customers_success_response_result_customers import UpdateCustomersSuccessResponseResultCustomers

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomersSuccessResponseResultCustomers from a JSON string
update_customers_success_response_result_customers_instance = UpdateCustomersSuccessResponseResultCustomers.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomersSuccessResponseResultCustomers.to_json())

# convert the object into a dict
update_customers_success_response_result_customers_dict = update_customers_success_response_result_customers_instance.to_dict()
# create an instance of UpdateCustomersSuccessResponseResultCustomers from a dict
update_customers_success_response_result_customers_from_dict = UpdateCustomersSuccessResponseResultCustomers.from_dict(update_customers_success_response_result_customers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



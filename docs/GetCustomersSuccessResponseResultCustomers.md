# GetCustomersSuccessResponseResultCustomers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer** | [**List[GetCustomersSuccessResponseResultCustomersCustomerInner]**](GetCustomersSuccessResponseResultCustomersCustomerInner.md) |  | 

## Example

```python
from entrata_api_client.models.get_customers_success_response_result_customers import GetCustomersSuccessResponseResultCustomers

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomersSuccessResponseResultCustomers from a JSON string
get_customers_success_response_result_customers_instance = GetCustomersSuccessResponseResultCustomers.from_json(json)
# print the JSON string representation of the object
print(GetCustomersSuccessResponseResultCustomers.to_json())

# convert the object into a dict
get_customers_success_response_result_customers_dict = get_customers_success_response_result_customers_instance.to_dict()
# create an instance of GetCustomersSuccessResponseResultCustomers from a dict
get_customers_success_response_result_customers_from_dict = GetCustomersSuccessResponseResultCustomers.from_dict(get_customers_success_response_result_customers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



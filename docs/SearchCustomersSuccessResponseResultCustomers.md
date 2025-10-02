# SearchCustomersSuccessResponseResultCustomers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer** | [**List[SearchCustomersSuccessResponseResultCustomersCustomerInner]**](SearchCustomersSuccessResponseResultCustomersCustomerInner.md) |  | 

## Example

```python
from entrata_api_client.models.search_customers_success_response_result_customers import SearchCustomersSuccessResponseResultCustomers

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCustomersSuccessResponseResultCustomers from a JSON string
search_customers_success_response_result_customers_instance = SearchCustomersSuccessResponseResultCustomers.from_json(json)
# print the JSON string representation of the object
print(SearchCustomersSuccessResponseResultCustomers.to_json())

# convert the object into a dict
search_customers_success_response_result_customers_dict = search_customers_success_response_result_customers_instance.to_dict()
# create an instance of SearchCustomersSuccessResponseResultCustomers from a dict
search_customers_success_response_result_customers_from_dict = SearchCustomersSuccessResponseResultCustomers.from_dict(search_customers_success_response_result_customers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



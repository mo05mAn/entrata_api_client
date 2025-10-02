# GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersCustomer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique identifier for the customer associated with the lease. | 
**first_name** | **str** | The first name of the customer. | [optional] 
**last_name** | **str** | The last name of the customer. | [optional] 
**is_active_bankruptcy** | **bool** | The Bankruptcy status of customer . | [optional] 
**bankruptcy_date** | **str** | The Bankruptcy date of customer. | [optional] 
**bankruptcy_note** | **str** | XYZ | [optional] 

## Example

```python
from openapi_client.models.get_lease_ar_transactions_success_response_response_result_leases_lease_customers_customer import GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersCustomer

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersCustomer from a JSON string
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_customer_instance = GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersCustomer.from_json(json)
# print the JSON string representation of the object
print(GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersCustomer.to_json())

# convert the object into a dict
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_customer_dict = get_lease_ar_transactions_success_response_response_result_leases_lease_customers_customer_instance.to_dict()
# create an instance of GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersCustomer from a dict
get_lease_ar_transactions_success_response_response_result_leases_lease_customers_customer_from_dict = GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomersCustomer.from_dict(get_lease_ar_transactions_success_response_response_result_leases_lease_customers_customer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



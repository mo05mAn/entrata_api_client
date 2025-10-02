# GetLeaseArTransactionsSuccessResponseResponseResultLeasesLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique identifier for the lease. | 
**property_id** | **int** | The identifier for the property associated with the lease. | [optional] 
**unit_space_id** | **int** | The identifier for the unit space associated with the lease. | [optional] 
**customers** | [**GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomers**](GetLeaseArTransactionsSuccessResponseResponseResultLeasesLeaseCustomers.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_lease_ar_transactions_success_response_response_result_leases_lease import GetLeaseArTransactionsSuccessResponseResponseResultLeasesLease

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseArTransactionsSuccessResponseResponseResultLeasesLease from a JSON string
get_lease_ar_transactions_success_response_response_result_leases_lease_instance = GetLeaseArTransactionsSuccessResponseResponseResultLeasesLease.from_json(json)
# print the JSON string representation of the object
print(GetLeaseArTransactionsSuccessResponseResponseResultLeasesLease.to_json())

# convert the object into a dict
get_lease_ar_transactions_success_response_response_result_leases_lease_dict = get_lease_ar_transactions_success_response_response_result_leases_lease_instance.to_dict()
# create an instance of GetLeaseArTransactionsSuccessResponseResponseResultLeasesLease from a dict
get_lease_ar_transactions_success_response_response_result_leases_lease_from_dict = GetLeaseArTransactionsSuccessResponseResponseResultLeasesLease.from_dict(get_lease_ar_transactions_success_response_response_result_leases_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



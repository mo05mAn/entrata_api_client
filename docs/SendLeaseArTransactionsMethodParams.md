# SendLeaseArTransactionsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transaction_id** | **int** | This is a required field. This field accepts single value. Unique Transaction ID of client system | 
**lease_id** | **int** | This is a required field. This field accepts single value. Lease ID | 
**ar_code_id** | **int** | This is a required field. This field accepts single value. Ar Code ID | 
**transaction_amount** | **int** | This is a required field. This field accepts single value. Transaction Amount | 
**transaction_date** | **date** | This is a required field. This field accepts single value. transactionDate | 
**ar_post_month** | **str** | This is an optional field. This field accepts single value. Charge Posting Month | [optional] 

## Example

```python
from openapi_client.models.send_lease_ar_transactions_method_params import SendLeaseArTransactionsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactionsMethodParams from a JSON string
send_lease_ar_transactions_method_params_instance = SendLeaseArTransactionsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactionsMethodParams.to_json())

# convert the object into a dict
send_lease_ar_transactions_method_params_dict = send_lease_ar_transactions_method_params_instance.to_dict()
# create an instance of SendLeaseArTransactionsMethodParams from a dict
send_lease_ar_transactions_method_params_from_dict = SendLeaseArTransactionsMethodParams.from_dict(send_lease_ar_transactions_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



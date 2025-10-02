# SendLeaseArTransactions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendLeaseArTransactionsMethod**](SendLeaseArTransactionsMethod.md) |  | 

## Example

```python
from openapi_client.models.send_lease_ar_transactions import SendLeaseArTransactions

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactions from a JSON string
send_lease_ar_transactions_instance = SendLeaseArTransactions.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactions.to_json())

# convert the object into a dict
send_lease_ar_transactions_dict = send_lease_ar_transactions_instance.to_dict()
# create an instance of SendLeaseArTransactions from a dict
send_lease_ar_transactions_from_dict = SendLeaseArTransactions.from_dict(send_lease_ar_transactions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



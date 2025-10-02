# GetLeaseArTransactions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeaseArTransactionsMethod**](GetLeaseArTransactionsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_lease_ar_transactions import GetLeaseArTransactions

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseArTransactions from a JSON string
get_lease_ar_transactions_instance = GetLeaseArTransactions.from_json(json)
# print the JSON string representation of the object
print(GetLeaseArTransactions.to_json())

# convert the object into a dict
get_lease_ar_transactions_dict = get_lease_ar_transactions_instance.to_dict()
# create an instance of GetLeaseArTransactions from a dict
get_lease_ar_transactions_from_dict = GetLeaseArTransactions.from_dict(get_lease_ar_transactions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



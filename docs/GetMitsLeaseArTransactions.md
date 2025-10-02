# GetMitsLeaseArTransactions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetMitsLeaseArTransactionsMethod**](GetMitsLeaseArTransactionsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_mits_lease_ar_transactions import GetMitsLeaseArTransactions

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeaseArTransactions from a JSON string
get_mits_lease_ar_transactions_instance = GetMitsLeaseArTransactions.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeaseArTransactions.to_json())

# convert the object into a dict
get_mits_lease_ar_transactions_dict = get_mits_lease_ar_transactions_instance.to_dict()
# create an instance of GetMitsLeaseArTransactions from a dict
get_mits_lease_ar_transactions_from_dict = GetMitsLeaseArTransactions.from_dict(get_mits_lease_ar_transactions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



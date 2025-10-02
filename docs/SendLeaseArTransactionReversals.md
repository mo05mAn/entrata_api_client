# SendLeaseArTransactionReversals


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendLeaseArTransactionReversalsMethod**](SendLeaseArTransactionReversalsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_lease_ar_transaction_reversals import SendLeaseArTransactionReversals

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactionReversals from a JSON string
send_lease_ar_transaction_reversals_instance = SendLeaseArTransactionReversals.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactionReversals.to_json())

# convert the object into a dict
send_lease_ar_transaction_reversals_dict = send_lease_ar_transaction_reversals_instance.to_dict()
# create an instance of SendLeaseArTransactionReversals from a dict
send_lease_ar_transaction_reversals_from_dict = SendLeaseArTransactionReversals.from_dict(send_lease_ar_transaction_reversals_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



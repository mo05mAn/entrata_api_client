# SendLeaseArTransactionReversalsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendLeaseArTransactionReversalsMethodParams**](SendLeaseArTransactionReversalsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_lease_ar_transaction_reversals_method import SendLeaseArTransactionReversalsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactionReversalsMethod from a JSON string
send_lease_ar_transaction_reversals_method_instance = SendLeaseArTransactionReversalsMethod.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactionReversalsMethod.to_json())

# convert the object into a dict
send_lease_ar_transaction_reversals_method_dict = send_lease_ar_transaction_reversals_method_instance.to_dict()
# create an instance of SendLeaseArTransactionReversalsMethod from a dict
send_lease_ar_transaction_reversals_method_from_dict = SendLeaseArTransactionReversalsMethod.from_dict(send_lease_ar_transaction_reversals_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



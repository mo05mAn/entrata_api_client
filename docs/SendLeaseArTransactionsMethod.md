# SendLeaseArTransactionsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendLeaseArTransactionsMethodParams**](SendLeaseArTransactionsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_lease_ar_transactions_method import SendLeaseArTransactionsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactionsMethod from a JSON string
send_lease_ar_transactions_method_instance = SendLeaseArTransactionsMethod.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactionsMethod.to_json())

# convert the object into a dict
send_lease_ar_transactions_method_dict = send_lease_ar_transactions_method_instance.to_dict()
# create an instance of SendLeaseArTransactionsMethod from a dict
send_lease_ar_transactions_method_from_dict = SendLeaseArTransactionsMethod.from_dict(send_lease_ar_transactions_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



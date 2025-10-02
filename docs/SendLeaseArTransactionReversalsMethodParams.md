# SendLeaseArTransactionReversalsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transaction_id** | **int** | This is a required field. This field accepts single value. This ID represents the \&quot;reference_id\&quot; provided in the sendLeaseArTrans actions response or the \&quot;TransactionID\&quot; provided in getMitsLeaseArTran sactions. | 
**transaction_amount** | **int** | This is a required field. This field accepts single value. The amount for which the original charge was posted. If the Original c harge was a negative charge, a credit, please send this amount as nega tive as well. | 
**property_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**reverse_date** | **date** | This is an optional field. This field accepts single value. This is an optional parameter. If a date is sent in this parameter, we will set this value as postDate for the reversed transactions. | [optional] 
**description** | **str** | This is an optional field. This field accepts single value. This is an optional parameter. We highly recommend that you provide a detailed description of the reason for which the charged is reversed. | [optional] 

## Example

```python
from entrata_api_client.models.send_lease_ar_transaction_reversals_method_params import SendLeaseArTransactionReversalsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactionReversalsMethodParams from a JSON string
send_lease_ar_transaction_reversals_method_params_instance = SendLeaseArTransactionReversalsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactionReversalsMethodParams.to_json())

# convert the object into a dict
send_lease_ar_transaction_reversals_method_params_dict = send_lease_ar_transaction_reversals_method_params_instance.to_dict()
# create an instance of SendLeaseArTransactionReversalsMethodParams from a dict
send_lease_ar_transaction_reversals_method_params_from_dict = SendLeaseArTransactionReversalsMethodParams.from_dict(send_lease_ar_transaction_reversals_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



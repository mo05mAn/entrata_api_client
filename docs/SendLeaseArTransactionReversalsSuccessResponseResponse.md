# SendLeaseArTransactionReversalsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**result** | [**SendLeaseArTransactionReversalsSuccessResponseResponseResult**](SendLeaseArTransactionReversalsSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_lease_ar_transaction_reversals_success_response_response import SendLeaseArTransactionReversalsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactionReversalsSuccessResponseResponse from a JSON string
send_lease_ar_transaction_reversals_success_response_response_instance = SendLeaseArTransactionReversalsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactionReversalsSuccessResponseResponse.to_json())

# convert the object into a dict
send_lease_ar_transaction_reversals_success_response_response_dict = send_lease_ar_transaction_reversals_success_response_response_instance.to_dict()
# create an instance of SendLeaseArTransactionReversalsSuccessResponseResponse from a dict
send_lease_ar_transaction_reversals_success_response_response_from_dict = SendLeaseArTransactionReversalsSuccessResponseResponse.from_dict(send_lease_ar_transaction_reversals_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



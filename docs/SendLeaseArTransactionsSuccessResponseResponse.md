# SendLeaseArTransactionsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**result** | [**SendLeaseArTransactionsSuccessResponseResponseResult**](SendLeaseArTransactionsSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_lease_ar_transactions_success_response_response import SendLeaseArTransactionsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseArTransactionsSuccessResponseResponse from a JSON string
send_lease_ar_transactions_success_response_response_instance = SendLeaseArTransactionsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendLeaseArTransactionsSuccessResponseResponse.to_json())

# convert the object into a dict
send_lease_ar_transactions_success_response_response_dict = send_lease_ar_transactions_success_response_response_instance.to_dict()
# create an instance of SendLeaseArTransactionsSuccessResponseResponse from a dict
send_lease_ar_transactions_success_response_response_from_dict = SendLeaseArTransactionsSuccessResponseResponse.from_dict(send_lease_ar_transactions_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



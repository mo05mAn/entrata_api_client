# GetLeaseArTransactionsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary identifier used to trace or track the request. | [optional] 
**code** | **int** | Successful response code. | 
**result** | [**GetLeaseArTransactionsSuccessResponseResponseResult**](GetLeaseArTransactionsSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_lease_ar_transactions_success_response_response import GetLeaseArTransactionsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseArTransactionsSuccessResponseResponse from a JSON string
get_lease_ar_transactions_success_response_response_instance = GetLeaseArTransactionsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeaseArTransactionsSuccessResponseResponse.to_json())

# convert the object into a dict
get_lease_ar_transactions_success_response_response_dict = get_lease_ar_transactions_success_response_response_instance.to_dict()
# create an instance of GetLeaseArTransactionsSuccessResponseResponse from a dict
get_lease_ar_transactions_success_response_response_from_dict = GetLeaseArTransactionsSuccessResponseResponse.from_dict(get_lease_ar_transactions_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



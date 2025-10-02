# CancelLeaseSuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | The status of the operation. | [optional] 
**message** | **str** | A message describing the result of the operation. | [optional] 

## Example

```python
from entrata_api_client.models.cancel_lease_success_response_result import CancelLeaseSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of CancelLeaseSuccessResponseResult from a JSON string
cancel_lease_success_response_result_instance = CancelLeaseSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(CancelLeaseSuccessResponseResult.to_json())

# convert the object into a dict
cancel_lease_success_response_result_dict = cancel_lease_success_response_result_instance.to_dict()
# create an instance of CancelLeaseSuccessResponseResult from a dict
cancel_lease_success_response_result_from_dict = CancelLeaseSuccessResponseResult.from_dict(cancel_lease_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



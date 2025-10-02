# CancelLeaseSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response status code. | 
**result** | [**CancelLeaseSuccessResponseResult**](CancelLeaseSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.cancel_lease_success_response import CancelLeaseSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of CancelLeaseSuccessResponse from a JSON string
cancel_lease_success_response_instance = CancelLeaseSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(CancelLeaseSuccessResponse.to_json())

# convert the object into a dict
cancel_lease_success_response_dict = cancel_lease_success_response_instance.to_dict()
# create an instance of CancelLeaseSuccessResponse from a dict
cancel_lease_success_response_from_dict = CancelLeaseSuccessResponse.from_dict(cancel_lease_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



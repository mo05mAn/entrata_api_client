# MoveInLeaseSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **str** | Response status code | 
**result** | [**MoveInLeaseSuccessResponseResult**](MoveInLeaseSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.move_in_lease_success_response import MoveInLeaseSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MoveInLeaseSuccessResponse from a JSON string
move_in_lease_success_response_instance = MoveInLeaseSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(MoveInLeaseSuccessResponse.to_json())

# convert the object into a dict
move_in_lease_success_response_dict = move_in_lease_success_response_instance.to_dict()
# create an instance of MoveInLeaseSuccessResponse from a dict
move_in_lease_success_response_from_dict = MoveInLeaseSuccessResponse.from_dict(move_in_lease_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



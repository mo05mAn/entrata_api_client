# MoveInLeaseSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the move-in request | 
**message** | **str** | Message regarding the move-in request | 

## Example

```python
from entrata_api_client.models.move_in_lease_success_response_result import MoveInLeaseSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of MoveInLeaseSuccessResponseResult from a JSON string
move_in_lease_success_response_result_instance = MoveInLeaseSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(MoveInLeaseSuccessResponseResult.to_json())

# convert the object into a dict
move_in_lease_success_response_result_dict = move_in_lease_success_response_result_instance.to_dict()
# create an instance of MoveInLeaseSuccessResponseResult from a dict
move_in_lease_success_response_result_from_dict = MoveInLeaseSuccessResponseResult.from_dict(move_in_lease_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# MoveOutLeaseSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the move-out request | 
**message** | **str** | Message regarding the move-out request | 

## Example

```python
from entrata_api_client.models.move_out_lease_success_response_result import MoveOutLeaseSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of MoveOutLeaseSuccessResponseResult from a JSON string
move_out_lease_success_response_result_instance = MoveOutLeaseSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(MoveOutLeaseSuccessResponseResult.to_json())

# convert the object into a dict
move_out_lease_success_response_result_dict = move_out_lease_success_response_result_instance.to_dict()
# create an instance of MoveOutLeaseSuccessResponseResult from a dict
move_out_lease_success_response_result_from_dict = MoveOutLeaseSuccessResponseResult.from_dict(move_out_lease_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



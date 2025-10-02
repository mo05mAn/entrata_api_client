# MoveOutLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**MoveOutLeaseMethod**](MoveOutLeaseMethod.md) |  | 

## Example

```python
from openapi_client.models.move_out_lease import MoveOutLease

# TODO update the JSON string below
json = "{}"
# create an instance of MoveOutLease from a JSON string
move_out_lease_instance = MoveOutLease.from_json(json)
# print the JSON string representation of the object
print(MoveOutLease.to_json())

# convert the object into a dict
move_out_lease_dict = move_out_lease_instance.to_dict()
# create an instance of MoveOutLease from a dict
move_out_lease_from_dict = MoveOutLease.from_dict(move_out_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



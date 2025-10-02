# MoveInLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**MoveInLeaseMethod**](MoveInLeaseMethod.md) |  | 

## Example

```python
from openapi_client.models.move_in_lease import MoveInLease

# TODO update the JSON string below
json = "{}"
# create an instance of MoveInLease from a JSON string
move_in_lease_instance = MoveInLease.from_json(json)
# print the JSON string representation of the object
print(MoveInLease.to_json())

# convert the object into a dict
move_in_lease_dict = move_in_lease_instance.to_dict()
# create an instance of MoveInLease from a dict
move_in_lease_from_dict = MoveInLease.from_dict(move_in_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



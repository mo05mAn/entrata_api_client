# MoveInLeaseMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**MoveInLeaseMethodParams**](MoveInLeaseMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.move_in_lease_method import MoveInLeaseMethod

# TODO update the JSON string below
json = "{}"
# create an instance of MoveInLeaseMethod from a JSON string
move_in_lease_method_instance = MoveInLeaseMethod.from_json(json)
# print the JSON string representation of the object
print(MoveInLeaseMethod.to_json())

# convert the object into a dict
move_in_lease_method_dict = move_in_lease_method_instance.to_dict()
# create an instance of MoveInLeaseMethod from a dict
move_in_lease_method_from_dict = MoveInLeaseMethod.from_dict(move_in_lease_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



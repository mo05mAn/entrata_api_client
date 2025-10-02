# MoveOutLeaseMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**MoveOutLeaseMethodParams**](MoveOutLeaseMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.move_out_lease_method import MoveOutLeaseMethod

# TODO update the JSON string below
json = "{}"
# create an instance of MoveOutLeaseMethod from a JSON string
move_out_lease_method_instance = MoveOutLeaseMethod.from_json(json)
# print the JSON string representation of the object
print(MoveOutLeaseMethod.to_json())

# convert the object into a dict
move_out_lease_method_dict = move_out_lease_method_instance.to_dict()
# create an instance of MoveOutLeaseMethod from a dict
move_out_lease_method_from_dict = MoveOutLeaseMethod.from_dict(move_out_lease_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# MoveInLeaseMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** |   This is a required field. This field accepts single value. | 
**lease_id** | **int** | This is a required field. This field accepts single value. | 

## Example

```python
from openapi_client.models.move_in_lease_method_params import MoveInLeaseMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of MoveInLeaseMethodParams from a JSON string
move_in_lease_method_params_instance = MoveInLeaseMethodParams.from_json(json)
# print the JSON string representation of the object
print(MoveInLeaseMethodParams.to_json())

# convert the object into a dict
move_in_lease_method_params_dict = move_in_lease_method_params_instance.to_dict()
# create an instance of MoveInLeaseMethodParams from a dict
move_in_lease_method_params_from_dict = MoveInLeaseMethodParams.from_dict(move_in_lease_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



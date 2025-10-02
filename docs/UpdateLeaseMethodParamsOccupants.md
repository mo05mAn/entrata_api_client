# UpdateLeaseMethodParamsOccupants

Optional object containing occupant details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**occupant** | [**List[UpdateLeaseMethodParamsOccupantsOccupantInner]**](UpdateLeaseMethodParamsOccupantsOccupantInner.md) | List of occupants | [optional] 

## Example

```python
from openapi_client.models.update_lease_method_params_occupants import UpdateLeaseMethodParamsOccupants

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeaseMethodParamsOccupants from a JSON string
update_lease_method_params_occupants_instance = UpdateLeaseMethodParamsOccupants.from_json(json)
# print the JSON string representation of the object
print(UpdateLeaseMethodParamsOccupants.to_json())

# convert the object into a dict
update_lease_method_params_occupants_dict = update_lease_method_params_occupants_instance.to_dict()
# create an instance of UpdateLeaseMethodParamsOccupants from a dict
update_lease_method_params_occupants_from_dict = UpdateLeaseMethodParamsOccupants.from_dict(update_lease_method_params_occupants_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



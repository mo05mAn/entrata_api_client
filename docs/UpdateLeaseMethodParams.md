# UpdateLeaseMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Accepts the single property Id that is associated with a lease. | 
**lease_id** | **int** | This is a required field. This field accepts single value. Accepts a single lease id for updating the lease details. | 
**unit_space_id** | **int** | This is an optional field. This field accepts single | [optional] 
**move_in_date** | **date** | This is a optional field. This field accepts single value. moveInDate (YYYY-MM-DD) | [optional] 
**occupants** | [**UpdateLeaseMethodParamsOccupants**](UpdateLeaseMethodParamsOccupants.md) |  | [optional] 
**customer_relationship_type_id** | **int** | This is a required field. This field accepts single value. customerRelationshipTypeId | 

## Example

```python
from entrata_api_client.models.update_lease_method_params import UpdateLeaseMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeaseMethodParams from a JSON string
update_lease_method_params_instance = UpdateLeaseMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateLeaseMethodParams.to_json())

# convert the object into a dict
update_lease_method_params_dict = update_lease_method_params_instance.to_dict()
# create an instance of UpdateLeaseMethodParams from a dict
update_lease_method_params_from_dict = UpdateLeaseMethodParams.from_dict(update_lease_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



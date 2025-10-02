# UpdateLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateLeaseMethod**](UpdateLeaseMethod.md) |  | 

## Example

```python
from entrata_api_client.models.update_lease import UpdateLease

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLease from a JSON string
update_lease_instance = UpdateLease.from_json(json)
# print the JSON string representation of the object
print(UpdateLease.to_json())

# convert the object into a dict
update_lease_dict = update_lease_instance.to_dict()
# create an instance of UpdateLease from a dict
update_lease_from_dict = UpdateLease.from_dict(update_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



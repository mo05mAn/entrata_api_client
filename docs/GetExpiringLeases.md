# GetExpiringLeases


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetExpiringLeasesMethod**](GetExpiringLeasesMethod.md) |  | 

## Example

```python
from openapi_client.models.get_expiring_leases import GetExpiringLeases

# TODO update the JSON string below
json = "{}"
# create an instance of GetExpiringLeases from a JSON string
get_expiring_leases_instance = GetExpiringLeases.from_json(json)
# print the JSON string representation of the object
print(GetExpiringLeases.to_json())

# convert the object into a dict
get_expiring_leases_dict = get_expiring_leases_instance.to_dict()
# create an instance of GetExpiringLeases from a dict
get_expiring_leases_from_dict = GetExpiringLeases.from_dict(get_expiring_leases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



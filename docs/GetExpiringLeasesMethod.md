# GetExpiringLeasesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetExpiringLeasesMethodParams**](GetExpiringLeasesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_expiring_leases_method import GetExpiringLeasesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetExpiringLeasesMethod from a JSON string
get_expiring_leases_method_instance = GetExpiringLeasesMethod.from_json(json)
# print the JSON string representation of the object
print(GetExpiringLeasesMethod.to_json())

# convert the object into a dict
get_expiring_leases_method_dict = get_expiring_leases_method_instance.to_dict()
# create an instance of GetExpiringLeasesMethod from a dict
get_expiring_leases_method_from_dict = GetExpiringLeasesMethod.from_dict(get_expiring_leases_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



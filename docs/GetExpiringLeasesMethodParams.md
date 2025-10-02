# GetExpiringLeasesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**from_date** | **date** | This is an optional field. This field accepts single value. Date from which leases are required | [optional] 
**to_date** | **date** | This is a required field. This field accepts single value. Date upto which leases are required | 
**is_month_to_month** | **int** | This is an optional field. This field accepts single value. Is Month To Month | [optional] 
**is_wait_list** | **int** | This is an optional field. This field accepts single value. If this parameter is enabled then we will show leases with lease type status notice and the property setting HIDE_NOTICE_RESIDENTS_FROM_RENE WALS should be disabled for this, else we will return error. | [optional] 

## Example

```python
from openapi_client.models.get_expiring_leases_method_params import GetExpiringLeasesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetExpiringLeasesMethodParams from a JSON string
get_expiring_leases_method_params_instance = GetExpiringLeasesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetExpiringLeasesMethodParams.to_json())

# convert the object into a dict
get_expiring_leases_method_params_dict = get_expiring_leases_method_params_instance.to_dict()
# create an instance of GetExpiringLeasesMethodParams from a dict
get_expiring_leases_method_params_from_dict = GetExpiringLeasesMethodParams.from_dict(get_expiring_leases_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


